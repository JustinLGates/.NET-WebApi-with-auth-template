# .NET-WebApi-with-auth-template

This template is set up with JwtBearer authentication, and database.

# Setup

## Step 1

use template to create your project

## Step 2

cd into your root directory. Using your terminal/CLI add the following packages
dotnet add package dapper
dotnet add package Microsoft.AspNetCore.Authentication.JwtBearer
dotnet add package MySqlConnector

## Step 3

Add app settings json files to the root directory

appsettings.json
appsettings.Development.json

These files are used to set the connection and authentication for your application.
The example below is what needs to go inside just add in your own credentals.

Example :

{

"DB": {
"gearhost": "server=serverName;port=3306;database=DBName;user id=username;password=yourpassword;"
},
"Auth0": {
"Domain": "yourAuth0Domain",
"Audience": "yourAuth0Audience"
}

}
