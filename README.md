## Required Software

.NET 6 SDK or Visual Studio 2022 (.NET for Web, F#)

## Build

```
dotnet publish ./homepage-backend.sln --arch x64 --configuration Release --output ./bin/
```

Output directory is `./bin`

Run `./bin/homepage-backend` (Mac & Linux) or `./bin/homepage-backend.exe` (Windows)

## Environment Variables

- `MAILGUN_API_KEY` Mailgun API Key
- `MAILGUN_DOMAIN_NAME` Mailgun API Domain
