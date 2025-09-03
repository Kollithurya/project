Morse Code Translator (Python)

Description
The Morse Code Translator is a Python project that can encode text into Morse code, decode Morse code back into text, and even play Morse code sounds (on Windows using `winsound`).  
This project demonstrates concepts like dictionaries, string manipulation, and control flow in Python.

Features
- Convert **text to Morse code**  
- Convert **Morse code to text**  
- Play Morse code as **audio beeps** (Windows only)  
- Interactive CLI menu  

Tech & Concepts Used
- Python 3
- Dictionaries for mapping characters to Morse code  
- String operations for encoding/decoding  
- Winsound module for audio playback (Windows-specific)  

Usage
1. Clone this repository or copy the project folder.  
2. Run the Python script:  
   ```bash
   python morse_code_translator.py
3.Choose from the menu:
1 → Text → Morse
2 → Morse → Text
3 → Play Morse audio
q → Quit

Sample Output
Welcome to Morse Code Translator!

Enter '1' to translate text to Morse code, '2' to translate Morse code to text, '3' to play Morse code, or 'q' to quit: 1
Enter the text to translate to Morse code: HELLO WORLD
Morse code: .... . .-.. .-.. ---   .-- --- .-. .-.. -..

Enter '1' to translate text to Morse code, '2' to translate Morse code to text, '3' to play Morse code, or 'q' to quit: 2
Enter the Morse code to translate to text: .... . .-.. .-.. ---   .-- --- .-. .-.. -..
Decoded text: HELLO WORLD
