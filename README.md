# FP-CSharp
HelloWorld backend project in C# with multiple API endpoints, connected to a React frontend. 

# FP-CSharp Project

## Overview
This project is a simple **HelloWorld backend** built with **C# and ASP.NET Core**, paired with a **React frontend**.  
It demonstrates how to expose API endpoints from a backend and consume them in a frontend application.

## Backend (C# / ASP.NET Core)
The backend provides multiple endpoints:
- `/api/hello` → returns `"Hello World from API"`
- `/api/time` → returns the current server time
- `/api/data` → returns a JSON object
- `/api/items` → returns a JSON list of items

### Run the backend
```bash
dotnet run
