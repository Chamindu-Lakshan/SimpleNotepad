# SimpleNotepad

A simple Notepad-like desktop application built using Java Swing.

## Features

- Text editing area
- File → Open, Save, Exit
- Scrollable text area
- Left margin for text readability

## Prerequisites

- Java JDK 17 or later installed on your machine
- (Optional) IntelliJ IDEA 2025.1.2 or later

---

## How to Run in IntelliJ IDEA

1. Open IntelliJ IDEA → **File → Open** → select the `SimpleNotepad` folder.  
2. Go to **File → Project Structure → Project**, make sure **Project SDK** points to your installed JDK.  
3. **Build → Rebuild Project**.  
4. Open `src/SimpleNotepad.java`.  
5. Right-click inside editor → **Run 'SimpleNotepad.main()'** or click the green ▶️ near the `main` method.  
6. The Notepad window will appear.

---

## How to Run from Command Line (CMD)

1. Open **Command Prompt**.  
2. Navigate to your project folder:

```cmd
cd path\to\SimpleNotepad
````

3. Compile the Java source file:

```cmd
javac -d out src\SimpleNotepad.java
```

* `-d out` tells the compiler to place `.class` files in the `out` folder.

4. Run the program:

```cmd
java -cp out SimpleNotepad
```

* `-cp out` tells Java where to find compiled classes.
* Make sure `SimpleNotepad.java` has `public static void main(String[] args)`.


---

## File Menu Usage

* **Open:** Load a text file into the editor.
* **Save:** Save current text to a file.
* **Exit:** Close the application.

---

## Notes

* If running from CMD, ensure your **JDK bin directory is in your PATH**.

## Credits 

This project was developed by W. Chamindu Lakshan.
University of Colombo

