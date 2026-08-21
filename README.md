<!-- Banner -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=header&text=Laravel%20Developer%20%7C%20PHP%20Developer&fontSize=40&fontAlignY=35&animation=twinkling&fontColor=fff" />
</p>

<!-- Laravel Badges -->
<p align="center">
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" />
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Livewire-4E56A2?style=for-the-badge&logo=livewire&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
</p>

<!-- Social Badges -->
<p align="center">
  <a href="https://github.com/AkubueAlexander">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/alexander-akubue-a635b6182">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>



## 👨‍💻 About Me

```php
<?php

namespace AkubueAlexander;

class Developer {
    public string $name = "Alexander Akubue";
    public string $role = "Full Stack PHP Developer";
    public array $specialties = ["Laravel", "Livewire", "REST APIs", "Database Design"];

    public function sayHello(): string {
        return "Building scalable web applications with Laravel 🚀";
    }
}

$me = new Developer();
echo $me->sayHello();
?>
