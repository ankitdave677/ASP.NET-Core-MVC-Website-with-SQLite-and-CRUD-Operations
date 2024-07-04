# ASSIGNMENT 2: ASP.NET Core MVC Website with SQLite and CRUD Operations

## Author
Name: Ankit Dave
Student Number: 8959634

### Steps to set up and run the project locally

#### Step 1: Unzip the project files
Download the project ZIP file from eConestoga Assignment 2 dropbox and extract it to a folder on your local machine.

#### Step 2: Install .NET Core SDK
Ensure that [.NET Core SDK](https://dotnet.microsoft.com/download) is installed on your machine.

#### Step 3: Navigate to Project Directory
Open a terminal or command prompt.
   cd path/to/Assignment2

#### Step 4: Restore Dependencies
Restore the necessary dependencies for the project by running the following command.
    dotnet restore

#### Step 5: Run Migrations
Execute Entity Framework Core migrations to set up the SQLite database by running the following command.
    dotnet ef database update

#### Step 6: Start and run the Application
Run the application by running the following command
    dotnet run
Now open the web browser and navigate to the port that is provided by the ASP.NET Server to run the application.

