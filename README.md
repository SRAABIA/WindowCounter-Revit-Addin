# Window Counter - REVIT Plugin

## Description
The Window Counter is a Revit add-in that counts the total number of window elements in a Revit project and displays the count in a task dialog.

## Features
- Counts the total number of windows in the active Revit document.
- Displays the window count in a task dialog.

## Prerequisites
- Autodesk Revit (2018 or later)
- .NET Framework 4.8
- Visual Studio 2019 or later

## Installation
1. **Clone the repository:**
    ```bash
    git clone https://github.com/SRAABIA/WindowCounter-Revit-Addin.git
    ```
2. **Open the solution in Visual Studio:**
    Navigate to the cloned repository folder and open the `WindowCounter.sln` file in Visual Studio.

3. **Build the solution:**
    - In Visual Studio, select `Build` > `Build Solution` or press `Ctrl+Shift+B`.

4. **Copy the Add-In Manifest:**
    - Copy the `counter.addin` file to the Revit Add-Ins folder, typically located at `C:\Users\HP\AppData\Roaming\Autodesk\Revit\Addins\2023`.

## Usage
1. **Open Autodesk Revit:**
    Launch Autodesk Revit.

2. **Load a Revit Project:**
    Open an existing project or create a new one.

3. **Run the Window Counter:**
    - In Revit, go to the `Add-Ins` tab.
    - Go to `External Tools`.
    - Select `Window Counter` to run the add-in.
    - A task dialog will appear displaying the total number of windows in the project.
## Output
![img1](https://github.com/SRAABIA/WindowCounter-Revit-Addin/blob/main/p1.png)
![img2](https://github.com/SRAABIA/WindowCounter-Revit-Addin/blob/main/p2.png)


## Contributing
Feel free to fork the repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## Contact
For any questions or issues, please contact me at sraabiahh@gmail.com .

## Acknowledgments
- Autodesk for providing the Revit API.
- [The BIM Mentor - Tutorial](https://www.youtube.com/watch?v=GM7b7j_u8a8)
