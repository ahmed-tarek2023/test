# Bulky_Web_MVC

A web application built using ASP.NET Core MVC, designed for managing categories and products with a clean Model-View-Controller architecture. This project is ideal as a learning resource or a scalable template for your own web applications.

---

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

---

## Features

- **Category Management**: Add, edit, and delete categories.
- **Product Management**: Full CRUD support for products.
- **MVC Pattern**: Follows best practices for separation of concerns.
- **Entity Framework**: Easy database integration and migrations.
- **Responsive UI**: Built with Bootstrap for a modern look.
- **Validation**: Server-side validation for data integrity.
- **Authentication/Authorization**: (If implemented) User and role management.

---

## Tech Stack

- **Backend**: ASP.NET Core MVC (C#)
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **ORM**: Entity Framework Core
- **Database**: SQL Server (LocalDB by default)
- **Other Tools**: NuGet for package management

---

## Project Structure

```
Bulky_Web_MVC/
├── Controllers/         # MVC Controllers
├── Models/              # Data and View Models
├── Views/               # Razor Views
│   ├── Shared/
├── wwwroot/             # Static files (css, js, images)
├── Data/                # Database context, migrations
├── appsettings.json     # Configuration
├── Program.cs           # Entry point
├── Startup.cs           # App config/services
└── README.md            # Documentation
```

---

## Getting Started

### Prerequisites

- [.NET SDK 6.0+](https://dotnet.microsoft.com/en-us/download)
- [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) or LocalDB
- [Visual Studio 2022+](https://visualstudio.microsoft.com/downloads/) or any C# IDE

### Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/ahmed-tarek-2004/Bulky_Web_MVC.git
    cd Bulky_Web_MVC
    ```

2. **Restore dependencies:**
    ```bash
    dotnet restore
    ```

3. **Configure the database:**
    - Update your connection string in `appsettings.json`.
    - Run migrations:
      ```bash
      dotnet ef database update
      ```

4. **Run the application:**
    ```bash
    dotnet run
    ```
    - Open your browser at `https://localhost:5001` (or as shown in the terminal).

---

## Usage

- Use the **Categories** section to manage categories.
- Use the **Products** section for product management.
- (If enabled) Log in/register for restricted features.

---

## Screenshots

> _Tip: Place your screenshots or UI images in `wwwroot/images/` and link them here!_

| Home Page        | Category Management    | Product Management     |
|------------------|-----------------------|-----------------------|
| ![Home Screenshot](wwwroot/images/home.png) | ![Categories Screenshot](wwwroot/images/categories.png) | ![Products Screenshot](wwwroot/images/products.png) |

---

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgments

- [Microsoft ASP.NET Core MVC Documentation](https://docs.microsoft.com/aspnet/core/mvc/)
- [Bootstrap Documentation](https://getbootstrap.com/)
