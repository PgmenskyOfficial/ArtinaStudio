# ArtinaStudio Extensions Help

ArtinaStudio features a built-in **Extensions Manager** designed to extend the editor's capabilities dynamically using both source scripts and compiled libraries.

## Supported Extension Types

1. **C# Scripts (`.cs`)**
   - Plain text source code files.
   - Ideal for lightweight scripts, quick modifications, and user-defined automation.
   - Evaluated and handled dynamically by the application.

2. **DLL Libraries (`.dll`)**
   - Pre-compiled binary libraries.
   - Designed for advanced extensions, complex features, or multi-file plugins built in environments like Visual Studio.

---

## Features & Functionality

- **Automatic Scanning:** The manager automatically scans the local extensions directory upon startup and refresh:
  `%LocalAppData%\ArtinaStudio\Extensions`
- **State Persistence (Enabled / Disabled):** 
  - Each extension can be toggled using the status checkbox in the manager window.
  - The activation state is automatically synchronized and saved to `settings.json` under the `DisabledExtensions` list, ensuring your preferences are remembered across application restarts.
- **Modern UI:** Designed with a native dark mode integration (`dwmapi.dll`) to seamlessly match Windows aesthetics, alongside full localization support.

---

## How to Manage Extensions

1. Open ArtinaStudio.
2. Navigate to the main menu and select **Manage Extensions**.
3. Use the checkboxes next to each file to enable or disable them instantly.
4. Click **Open Folder** to quickly drop new `.cs` or `.dll` files into the extensions directory, then click **Refresh** to load them.
