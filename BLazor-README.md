# Blazor website preview

The original HTML proof-of-concept is in the repository root as `index.html` on the initial-design branch. This branch adds a .NET 10 Blazor Web App in `CorkMarineDeckSpecialists/`.

## Run locally
Install the .NET 10 SDK and run:

For IDE builds targeting .NET 10, use Visual Studio 2026 (18.0 or later). Visual Studio 2022 does not support targeting .NET 10; use the .NET 10 CLI if keeping that IDE installed.

```powershell
$env:ASPNETCORE_ENVIRONMENT = "Development"
dotnet run --project CorkMarineDeckSpecialists/CorkMarineDeckSpecialists.csproj
```

Open the localhost URL printed by the application.

This is a visual preview. The contact form intentionally does **not** send data. Genuine licensed photos, lead handling, service territory, and manufacturer warranty language require approval before publication.
