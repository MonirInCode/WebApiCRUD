# WebApiCRUD Project

This project is a Web API-based CRUD application where users can manage employee data and upload images. It includes database configuration, image storage, and CRUD functionality tested via Postman.

## Project Structure

### Directory Overview

- **wwwroot/Uploads**: Directory where uploaded images are stored.
- **Controllers**:
  - **EmployeeController.cs**: Handles CRUD operations for employee data.

- **Models and DTOs**:
  - **CommonDTO.cs**: Defines common data transfer objects used across the project.
  - **ImgUpload.cs**: Handles image upload functionality.
  - **AppDbContext.cs**: Configures database context for the application.
  - **Employee.cs**: Entity model representing employee data.
  - **Experience.cs**: Entity model representing employee experience.

- **Configuration**:
  - **appsettings.json**: Contains configuration settings, including database connection strings.

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/WebApiCRUD.git
   cd WebApiCRUD
   
### Configure Database:
Update the appsettings.json file with your database connection string.
Run the following command in the terminal to update the database:
- update-database

Run the Application:

Open the project in Visual Studio.
Run the following command in the terminal to update the database:
- update-database
Build and run the solution.
Testing CRUD Operations
## CRUD operations can be tested via Postman:

**Create:** POST /api/Employee  
**Read:** GET /api/Employee/{id}  
**Update:** PUT /api/Employee/{id}  
**Delete:** DELETE /api/Employee/{id}  
Ensure that images uploaded through the API are saved in the wwwroot/Uploads directory.

### Dependencies
.NET Core SDK
Entity Framework Core
Postman (for API testing)

## Contact
For questions or feedback, please reach out to monirgsc@gmail.com

## This README includes setup instructions, a breakdown of the project structure, and notes on testing CRUD operations with Postman. Let me know if you'd like more details or adjustments!
