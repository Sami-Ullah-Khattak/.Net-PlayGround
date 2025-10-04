
---

# 🧩 .Net-PlayGround

## 🐧 Linux (Fedora) Installation

| Step | Action               | Command                                                                     |
| ---- | -------------------- | --------------------------------------------------------------------------- |
| 1    | Install .NET SDK     | `sudo dnf install dotnet-sdk-8.0`                                           |
| 2    | Install VS Code      | `sudo dnf install code`                                                     |
| 3    | Install C# Extension | via VS Code Extensions (`C# for Visual Studio Code (powered by OmniSharp)`) |
| 4    | Create Project       | `dotnet new console`                                                        |
| 5    | Run Project          | `dotnet run`                                                                |
| 6    | Open in VS Code      | `code .`                                                                    |

---

## 🪟 Windows Installation

| Step | Action                         | Command / Link                                                                                                            |
| ---- | ------------------------------ | ------------------------------------------------------------------------------------------------------------------------- |
| 1    | **Install .NET SDK**           | Download and install from 👉 [https://dotnet.microsoft.com/download](https://dotnet.microsoft.com/download)               |
| 2    | **Install Visual Studio Code** | Download and install from 👉 [https://code.visualstudio.com/](https://code.visualstudio.com/)                             |
| 3    | **Install C# Extension**       | Open VS Code → Extensions (Ctrl+Shift+X) → Search **“C#”** → Install **C# for Visual Studio Code (powered by OmniSharp)** |
| 4    | **Create a New Project**       | Open PowerShell or Command Prompt → `dotnet new console -o MyApp`                                                         |
| 5    | **Run the Project**            | `cd MyApp` → `dotnet run`                                                                                                 |
| 6    | **Open in VS Code**            | `code .` (from project folder)                                                                                            |
| 7    | **Debug / Build**              | Press **F5** in VS Code or run `dotnet build`                                                                             |

---

### ✅ Verify Installation

To confirm setup works on **both Linux & Windows**, run:

```bash
dotnet --version
```

You should see something like:

```
8.0.x
```

Then:

```bash
dotnet new console -o TestApp
cd TestApp
dotnet run
```

Output:

```
Hello, World!
```

---