<p align="center">
  <a href="https://tutujokes.github.io/SaudePlus" target="_blank">
    <img src="https://img.shields.io/badge/Check_out_my_collab_project-SaudePlus-blueviolet?style=for-the-badge&logo=github" alt="SaudePlus Project"/>
  </a>
</p>

<img src="https://raw.githubusercontent.com/khoa083/khoa/main/Khoa_ne/img/Rainbow.gif" width="100%">

```php
<?php

class Me 
{
    public $project = "Check out my ongoing collab project: https://tutujokes.github.io/SaudePlus";

    public $name   = "Arthur Henrique";
    public $age    = 23;

    public $skills = [
        "Java Developer", 
        "SQL Database Management", 
        "Backend Developer"
    ];

    public $tools  = [
        "Java", "C", "Linux", 
        "Git & GitHub", "MySQL"
    ];

    public $interests = [
        "Docker", "Spring Boot", "PHP"
    ];

    private $secret = "Nothing Here I Swear...";

    public function __construct() {}

    public function sayHello() {
        echo "Welcome to my world.\n";
    }
}

$arthur = new Me();
$arthur->sayHello();
