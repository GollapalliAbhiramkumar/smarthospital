# SmartHospital (Java)

A beginner-friendly console prototype demonstrating one representative DSA algorithm from each of the six SmartHospital modules.

## Requirements
- JDK 17 or newer
- Visual Studio Code
- Extension Pack for Java (Microsoft)

## Open in VS Code
1. Extract `SmartHospital_VSCode.zip`.
2. In VS Code, choose **File → Open Folder** and open the extracted `SmartHospital_VSCode` folder.
3. Install the **Extension Pack for Java** if VS Code prompts you.
4. Open `src/smarthospital/SmartHospital.java`.
5. Click **Run** above `main`, or use the terminal commands below.

## Run from terminal
Open a terminal in the extracted project folder.

Windows:
```powershell
javac -d out src/smarthospital/SmartHospital.java
java -cp out smarthospital.SmartHospital
```

macOS/Linux:
```bash
javac -d out src/smarthospital/SmartHospital.java
java -cp out smarthospital.SmartHospital
```

## Menu
1. Display sample patient records
2. Search a medical term using KMP
3. Display a simple sorted suffix-array demonstration
4. Calculate Levenshtein edit distance
5. Calculate maximum flow using Edmonds-Karp
6. Demonstrate a 2-approximation for Vertex Cover
7. Sort sample numerical records using randomized QuickSort
0. Exit

## Notes
- The patient records are fictional sample data embedded in the source code.
- This is an academic demonstration, not a real hospital system.
- It implements representative algorithms only, not every algorithm listed in the full assignment.
- The suffix-array example is a straightforward educational implementation, not SA-IS.
