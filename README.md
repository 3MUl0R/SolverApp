# SolverApp

This is a .NET solution that contains multiple projects, including a Windows Forms application named `SolverApp`.

## Structure

The workspace contains the following main components:

- **SolverApp.sln**: The solution file that includes the `SolverApp` project and references to other projects like `LinearAlgebra` and `ClassStringCalc`.
- **SolverApp.csproj**: The project file for the `SolverApp` application.
- **Program.cs**: The entry point for the `SolverApp` application.
- **frmMain.cs**: The main form for the `SolverApp` application.
- **ConfigFileToCBCode**: A separate project in the workspace.
- **DLLs**: A directory containing various DLL files that are likely used by the projects.
- **bin** and **obj**: Directories generated by the build process, containing the build output.

## Building

To build the `SolverApp` project, you can use the build command in Visual Studio, or use `msbuild` from the command line:

```sh
msbuild SolverApp.csproj
```

This will generate the executable and other necessary files in the bin directory.

## Running
To run the SolverApp application, navigate to the bin directory and run the SolverApp.exe file.

## Dependencies
The SolverApp project depends on several DLLs, which are included in the DLLs directory. These include ClassStringCalc.dll, FileIO.dll, LinearAlgebra.dll, and SolverSDK.dll.

## Contributing
To contribute to this project, you can make changes to the source code and submit a pull request. Please make sure to test your changes thoroughly before submitting.

## License
This project is licensed under the terms of the MIT License.