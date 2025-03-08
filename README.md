# 👋 Hello, I'm Ar Jay Marigondon!  
##### 🎯 Web Developer | 💻 3+ Years in PHP | 🛠️ Code, Coffee ☕ / Water 💧, Repeat! 🚀
---

## 🚀 Tech Stack  

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white) ![Bootstrap](https://img.shields.io/badge/Bootstrap-712cf9?style=for-the-badge&logo=bootstrap&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/Tailwind%20CSS-00bcff?style=for-the-badge&logo=tailwindcss&logoColor=white) ![Laravel Livewire](https://img.shields.io/badge/Livewire-fb70a9?style=for-the-badge&logo=livewire&logoColor=white) ![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white) ![FilamentPHP](https://img.shields.io/badge/filamentphp-fdae4b?style=for-the-badge&logo=filament&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white) ![DigitalOcean](https://img.shields.io/badge/Digital%20Ocean-0080FF?style=for-the-badge&logo=digitalocean&logoColor=white)

## 🧑‍💻 Developer's Note  

```php
class Developer
{
    public $name = "Ar Jay Marigondon";
    public $role = "Web Developer";
    public $email = "jaydoesphp@gmail.com";
    public $tech_stack = ["PHP", "Laravel", "JavaScript", "Bootstrap", "MySQL"];
    public $tools = ["VS Code", "GitHub", "Terminal"];
    public $nonStopLearning = true;
    public $satisfied = false;

    public function getTools()
    {
        return [
            "Frameworks" => ["Laravel", "Laravel Livewire", "FilamentPHP"],
            "Frontend" => ["Bootstrap"],
            "Database" => ["MySQL"],
            "Other Tools" => ["Git"],
        ];
    }

    public function work()
    {
        while (!$this->satisfied) {
            $this->learnAndCode();
        }

        return "Happy Coding!";
    }

    public function letsCollaborate()
    {
        return "I'm open for collaboration! Reach me at: " . $this->email;
    }
}
