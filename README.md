# backend-scaffolding

A C# Web API backend scaffolded by POLAIRA.

## Tech Stack

- **App Name:** backend-scaffolding
- **Backend:** ASP.NET Core Web API
- **Language:** C#

## Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download) (see `global.json` for the required version, if present)

## Getting Started

```bash
# Clone the repository
git clone <repo-url>
cd backend-scaffolding

# Restore dependencies
dotnet restore

# Run the API
dotnet run
```

The API will be available at `https://localhost:5001` (or `http://localhost:5000`) by default.

## Project Structure

```
backend-scaffolding/
├── .gitignore
└── README.md
```

Additional directories (controllers, models, services, etc.) will be added as the project grows.

## Development

### Build

```bash
dotnet build
```

### Test

```bash
dotnet test
```

### Environment Variables

Copy `.env.example` to `.env` (if provided) and set any required values before running locally. The `.env` file is gitignored and should never be committed.
