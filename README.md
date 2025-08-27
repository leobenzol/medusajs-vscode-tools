# Medusa.js Snippets

A Visual Studio Code extension that provides useful code snippets and commands for Medusa.js development.

## Features

### Code Snippets
This extension provides the following snippets for Medusa.js development:

- `mrg` - Creates a GET API route
- `mrp` - Creates a POST API route  
- `mru` - Creates a PUT API route
- `mrd` - Creates a DELETE API route
- `mrw` - Creates a workflow
- `mrws` - Creates a workflow step


### Commands
- **Create Medusa Module**: Automatically generates a complete module structure with boilerplate files

## Usage

### Using Snippets
1. Open a TypeScript or JavaScript file
2. Type one of the snippet prefixes (e.g., `mrg`)
3. Press `Tab` or `Enter` to expand the snippet
4. Use `Tab` to navigate through the snippet placeholders

### Using Commands
1. Open the Command Palette (`Cmd+Shift+P` on Mac, `Ctrl+Shift+P` on Windows/Linux)
2. Type "Create Medusa Module"
3. Enter the name of your module (e.g., "user-management")
4. The extension will create the complete module structure in `src/modules/`

#### Module Structure Created
When you run the "Create Medusa Module" command, it generates:
```
src/modules/your-module-name/
├── index.ts          # Module definition and exports
├── service.ts        # Service class with CRUD methods
└── models/
    └── your-module-name.ts  # Model definition
```

## Snippets

### GET Route (`mrg`)
Creates a basic GET API route handler with proper Medusa.js imports and types.

### POST Route (`mrp`)
Creates a basic POST API route handler with async/await pattern.

### PUT Route (`mru`)
Creates a basic PUT API route handler for updating resources.

### DELETE Route (`mrd`)
Creates a basic DELETE API route handler that returns a 204 status.

## Requirements

- Visual Studio Code 1.74.0 or higher
- Medusa.js project

## Contributing

If you have suggestions for improvements or additional snippets, please feel free to contribute!

## License

MIT
