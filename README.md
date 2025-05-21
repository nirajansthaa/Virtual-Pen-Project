Virtual Pen Drawing In Canvas with Hand Gestures features

Description

Draw, erase, and interact with a virtual canvas using just your hands and a webcam — no mouse or stylus required!

This project utilizes real-time hand tracking to emulate a virtual pen, enabling users to select colors, draw freely, erase, clear the canvas, and save their artwork using intuitive hand gestures. It demonstrates the power of computer vision, gesture recognition, and creative human-computer interaction.


Features

✍️ Draw on screen with your index finger.

🟦 Choose colors from an on-screen palette using finger position.

👍 Save drawings with a simple thumbs-up gesture.

👌 Clear the canvas using the OK hand gesture.

🖐️ Erase parts of the drawing with your middle finger.

📂 Automatically saves images to a designated folder.

🧠 Gesture recognition based on Mediapipe's hand landmarks.

🎯 Includes cooldown timers to prevent multiple accidental actions.

Requirements

    Python 3.x
    OpenCV
    Mediapipe

How to Use

    Clone this repository to your local machine.

    Install the required dependencies on your working environment- pip install opencv-python mediapipe numpy 
    
    Run the script:py virtual_pen.py

    Interact using your hands:

    Use your index finger to draw.

    Hover over color boxes to change colors.

    Show a thumbs up to save.

    Show an OK gesture to clear the canvas.

    Use your middle finger (left hand) to erase.

Color Selection

To select a color, position your hand in the color regions at the top of the screen. The available colors are as follows:

    Black
    Red
    White
    Green
    Purple
    Yellow
    Blue
📜 License

This project is licensed under the MIT License.
