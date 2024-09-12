class Github {
    private $ten;
    private $lienhe;
    private $bietdanh;
    private $ip;
    private $tuoi;
    private $cv;
    private $may;

    // Constructor
    public function __construct() {
        $this->init();
    }

    // Initialize properties
    private function init() {
        $this->ten = "thanhsangdev";
        $this->lienhe = array(
            "telegram" => "sieutool08",
            "Facebook" => "axerdev",
        );
        $this->bietdanh = array("thanhsangdev", "codezgit.com");
        $this->ip = "localhost, vietnamese";
        $this->tuoi = "16+";
        $this->cv = "Web Developer";
        $this->may = "Windows 10 x 11";
    }

    // Getter methods
    public function getten() {
        return $this->ten;
    }

    public function getlienhe() {
        return $this->lienhe;
    }

    public function getbietdanh() {
        return $this->bietdanh;
    }

    public function getip() {
        return $this->ip;
    }

    public function gettuoi() {
        return $this->tuoi;
    }

    public function getcv() {
        return $this->cv;
    }

    public function getmay() {
        return $this->may;
    }
}

// Example usage
$github = new Github();
echo "ten: " . $github->getten() . "\n";
echo "ip: " . $github->getip() . "\n";
