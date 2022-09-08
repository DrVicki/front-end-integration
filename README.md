# FRONT-END INTEGRATION

## Walkthrough: Setting up the Back End

### Create a New Web API Application

The project for the back-end will be a .NET Core WebApi. It will be configured to accept requests and then return data to the client. Open the terminal and create a new project following the same steps as in previous lessons. Name the project BackendApplication.

**Terminal**

```
cd desktop
cd Programming/CSharp
dotnet new webapp -o BackendApplication --force
cd BackendApplication
code .
```

The preceding commands:

  - Changes directry to Desktop (or where your `Programming/CSharp` lives)
  - Changes directory to `Programming/CSharp`
  - Creates a new web app
    - The `-o BackendApplication` parameter creates a directory named BackendApplication with the source files for the app.
    
### Trust the development certificate

Trust the HTTPS development certificate:

`dotnet dev-certs https --trust`

The preceding command displays the following dialog:


















