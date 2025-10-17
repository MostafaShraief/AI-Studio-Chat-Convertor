
# AI Studio Chat Convertor

A command-line utility built with C# and .NET 9 for converting chat conversation formats. This tool is designed to process and transform chat data from one JSON structure to another, for use with AI Studio.

## Prerequisites

- .NET 9.0 SDK or later

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/MostafaShraief/AI-Studio-Chat-Convertor
   ```
2. **Navigate to the project directory:**
   ```bash
   cd "AI Studio Chat Convertor"
   ```
3. **Restore the .NET packages:**
   ```bash
   dotnet restore
   ```

## Usage

To run the application, execute the following command from the project's root directory:

```bash
dotnet run
```

### Configuration

The application's behavior can be configured through the following files:

- `config.json`: Main application configuration.
- `converter_settings.conf`: Specific settings for the converter.

## Dependencies

This project utilizes the following key dependency:

- **Newtonsoft.Json**: For efficient JSON manipulation.

## Project Structure

- `Program.cs`: The main entry point for the application.
- `AI Studio Chat Convertor.csproj`: The C# project file, defining project properties and dependencies.
- `/bin`: Contains the compiled output of the project.
- `/obj`: Contains intermediate files generated during the build process.
