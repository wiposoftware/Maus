# Servo brackets

## Overview
The Maus RC paramotor gondola supports mini (35.5x15) and standard (40x20) servos.<br/>
Within a given class, a servo's dimensions may differ slightly from the standard size. Before 3D printing the Maus gondola, it is crucial to test the servo fitting and note down the exact dimensions. <br/>
This repository contains two STL files: one for mini servos and one for standard servos. These STL files feature default dimensions typical for their respective classes.

## Guide
### step 1 
Download the "servo_fit_xxxx" STL file that corresponds to your servo class. Use the STL file in your 3D printer slicer software to print the test plate.<br />
<img width="320" height="280" alt="stb1" src="https://github.com/user-attachments/assets/3b64f65c-b5ae-4c69-8759-d62d21f05642" />
<img width="320" height="299" alt="stb2" src="https://github.com/user-attachments/assets/9f6b955f-ba1a-458f-8758-016ca3bb4925" /><br />

### step 2
Check that your servo fits properly into the test plate and that the servo mounting holes align with the holes in the test plate.<br />
<img width="320" height="243" alt="stb3" src="https://github.com/user-attachments/assets/f005c8ec-c06e-44d3-b263-6266f58c68e6" />
<img width="320" height="224" alt="stb4" src="https://github.com/user-attachments/assets/27b17b24-a099-4492-b162-37019b0afc62" />
<img width="320" height="174" alt="stb5" src="https://github.com/user-attachments/assets/4af6a15a-4a5e-4079-b178-300cc54b2dd1" /><br />

If this is not the case, adjust the dimensions of the test plate and print it again. **Repeat this step until your servo fits perfectly.**

To change the test plate dimension download the "servo_fit_test.FCStd" file use FreeCad to open it and change the values. You don't need any 3D design knowledge; dimensions can be adjusted using a simple selection box. Then, export your modifications to a new STL file and use it in your 3D printer slicer software.<br />
<img width="640" height="492" alt="stb6" src="https://github.com/user-attachments/assets/42314570-4755-471d-bb0e-60e6bb7d48c0" /><br />

### step 3
Okay, you have found the correct dimensions for the servo mount and noted down the values. We will not need this mount any further for the assembly of the Maus gondola.<br /><br />
The servos can be mounted in the gondola using screws and bolts; however, the limited space can make this a difficult task. To simplify the servo installation, a mounting aid is provided in the next step.

### step 4
If you used the default values ​​in the previous steps, you can download the "servo_bracket.stl" file and print it on your 3D printer.<br />
If you used custom values, you can download the "servo_bracket.FCStd" file and adjust the settings in FreeCAD—again, using simple selection boxes. Then, export to STL and print.<br />
<br />
<img width="640" height="584" alt="servo_bracket" src="https://github.com/user-attachments/assets/5111bb9f-f4c9-49fb-af14-f7cd682eb343" /><br /><br />

### step 5
For this bracket, I recommend using M3 threaded inserts (the default option). You can also use standard screws and nuts, though assembly is more difficult.<br />
<img width="320" alt="servo_bracket1" src="https://github.com/user-attachments/assets/824727d8-1233-4982-8fdd-871033c97a33" /><br /><br />

### step 6
Use tape to temporarily attach the servo mounting brackets to the servo. Make sure the M3 inserts are facing downwards.<br />
<img width="320" alt="servo_bracket3" src="https://github.com/user-attachments/assets/54838404-ef0b-4747-8f6d-97c13a500efc" />
<img width="320" alt="servo_bracket2" src="https://github.com/user-attachments/assets/4f92e264-1505-4936-807e-de41d42d9aa2" /><br /><br />

### step 7
Now, use the servo-fitting template from step 1 one last time. Use a few screws to check that all parts and holes align perfectly.<br />
If they do not align, you will need to adjust the dimensions of the mounting template and print it again.<br />
<img width="320" alt="servo_bracket4" src="https://github.com/user-attachments/assets/86780233-cbb7-4b91-bcbe-fe12c4623cfc" />
<img width="320" alt="servo_bracket5" src="https://github.com/user-attachments/assets/4b803fab-a58a-4548-bb3e-81a932887362" /><br /><br />












