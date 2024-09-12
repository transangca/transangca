<?php

class Github {
    private $username;
    private $contacts;
    private $aliases;
    private $location;
    private $age;
    private $occupation;
    private $operating_system;

    // Constructor
    public function __construct() {
        $this->init();
    }

    // Initialize properties
    private function init() {
        $this->username = "thanhdieutv";
        $this->contacts = array(
            "Discord" => "thanhdieutv#2278",
            "Facebook" => "WusThanhDieu",
        );
        $this->aliases = array("thanhdieudev", "Tdv");
        $this->location = "localhost, vietnamese";
        $this->age = "22+";
        $this->occupation = "Freelance Developer";
        $this->operating_system = "Windows, Arch, Linux, VPS";
    }

    // Getter methods
    public function getUsername() {
        return $this->username;
    }

    public function getContacts() {
        return $this->contacts;
    }

    public function getAliases() {
        return $this->aliases;
    }

    public function getLocation() {
        return $this->location;
    }

    public function getAge() {
        return $this->age;
    }

    public function getOccupation() {
        return $this->occupation;
    }

    public function getOperatingSystem() {
        return $this->operating_system;
    }
}

// Example usage
$github = new Github();
echo "Username: " . $github->getUsername() . "\n";
echo "Location: " . $github->getLocation() . "\n";
