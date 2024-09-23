
<h1>Eye-Blink Controlled Virtual Keyboard</h1>
<p>This project allows the creation of a virtual keyboard controlled by eye blinks using computer vision and facial landmark detection via the <code>dlib</code> library. The program captures real-time video from your webcam, tracks your face and eyes, and allows you to select keys through blink interactions.</p>

<h2>Prerequisites</h2>
<p>Ensure you have the following dependencies installed before running the project:</p>
<ul>
    <li><a href="https://pypi.org/project/opencv-python/" target="_blank">OpenCV</a></li>
    <li><a href="https://pypi.org/project/numpy/" target="_blank">NumPy</a></li>
    <li><a href="http://dlib.net/" target="_blank">dlib</a></li>
</ul>

<h2>How to Use</h2>
<ol>
    <li>Once the script runs, a window will open showing the camera feed with a rectangular frame around your face.</li>
    <li>The virtual keyboard will be displayed on the screen.</li>
    <li>Blink to select a column of keys. The next blink will allow you to select a key within the chosen column.</li>
    <li>Selected letters will appear in a display area at the top left of the screen.</li>
    <li>To exit, press the 'Esc' key.</li>
</ol>

<h2>Customization</h2>
<ul>
    <li>Modify the <code>keyset</code> dictionary in the code to customize the keys on the virtual keyboard.</li>
    <li>You can also adjust the layout of the keys in the <code>letter</code> function to match your preference.</li>
    <li>Fine-tune the blink detection thresholds in the <code>get_eyes_ratios</code> function to improve blink recognition accuracy.</li>
</ul>

<h2>Notes</h2>
<p>This script provides a basic layout for a blink-controlled keyboard. You can modify it further based on your specific use case and user interface preferences.</p>

<h2>Acknowledgments</h2>
<p>The facial landmark predictor model is provided by the <a href="http://dlib.net/" target="_blank">dlib library</a>.</p>

<h2>License</h2>
<p>This project is released under the MIT License. Feel free to use, modify, and distribute the code as needed.</p>

</body>
</html>
