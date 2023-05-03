<h1>My Demo Video</h1>

https://user-images.githubusercontent.com/90223955/236015227-2e2da4b7-e636-4ed8-b753-d51eb4381315.mp4


<h2>Things used in this project</h2>

<h3>Hardware components</h3>
<ul>
    <li>Breadboard (generic)</li>
    <li>7 Segment 4 Digit LED</li>
    <li>Jumper wires (generic)</li>
    <li>Resistor 330 ohm</li>
    <li>Arduino UNO</li>
</ul>

<h3>Software apps and online services:</h3>
<ul>
    <li>Arduino IDE</li>
    <li>Jupyter Notebook</li>
    <li>OpenCV</li>
</ul>

<h2>Story</h2>

<h3>INTRODUCTION:</h3>
<p>Gesture recognition helps computers to understand human body language. This helps to build a more potent link between humans and machines, rather than just the basic text user interfaces or graphical user interfaces (GUIs).</p>

<p>In this project, we are using gestures (by extracting the key points from the library), setting conditions based on the gestures that the code reads and sending data to Arduino to turn the LEDs on/off.</p>

<p>The gesture 1 lets you turn on LED-1, 2 for LED- 2, 3 for LED-3, 5 for turning all the LEDs off and 0 for exiting.</p>

<h3>OpenCV:</h3>
<p>OpenCV (Open-Source Computer Vision Library) is an open-source computer vision and machine learning software library. OpenCV was built to provide a common infrastructure for computer vision applications and to accelerate the use of machine perception in commercial products.</p>

<h3>Mediapipe:</h3>
<p>Mediapipe is an open-source machine learning library of Google, which has some solutions for face recognition and gesture recognition and provides encapsulation of python, js, and other languages. MediaPipe Hand is a high-fidelity hand and finger tracking solution. It uses machine learning (ML) to infer 21 key 3D hand information from just one frame.</p>

<h3>CvZone:</h3>
<p>Cvzone is the library that develops a bridge between Arduino and python. With the help of the SerialObject module in Cvzone we can connect the Arduino port with Python as well as send data to Arduino and can link any Python code with it.</p>

<h2>APPROACH:</h2>
<ol>
    <li>Detect hand gestures.</li>
    <li>Code reads the gestures.</li>
    <li>Every gesture has different conditions.</li>
    <li>Based on the condition, send the data to Arduino.</li>
    <li>Show result on 7 segment LED.</li>
</ol>


