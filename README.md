# Yazilim_2D1S

## Description
The repository contains a C# project for an e-commerce application using Entity Framework Core and SQL Server. It includes database context configuration, migration scripts, and documentation on setting up the database and running the application.

## Features
- **Entity Framework Core**: ORM for managing database operations.
- **SQL Server**: Relational database management system.
- **Database Context Configuration**: Setup for interacting with the database.
- **Migration Scripts**: Tools for updating the database schema.
- **Documentation**: Instructions on setting up the database and running the application.

## Installation
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/Yazilim_2D1S.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Yazilim_2D1S
   ```

3. Install the required NuGet packages by running:
   ```bash
   dotnet restore
   ```

4. Set up the database using Entity Framework Core migrations:
   - Create a new migration:
     ```bash
     dotnet ef migrations add InitialCreate
     ```
   - Update the database:
     ```bash
     dotnet ef database update
     ```

## Usage
1. Run the application:
   ```bash
   dotnet run
   ```

2. Access the e-commerce application in your web browser at `http://localhost:5000`.

## Tech Stack
- C#
- Entity Framework Core
- SQL Server

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

For more information on setting up the database and running the application, please refer to the following documents:
- [Sınav_Soru.md](Sınav_Soru.md)
- [VeriTabaniOlusturma.md](VeriTabaniOlusturma.md)

If you have any questions or need further assistance, feel free to open an issue in this repository.