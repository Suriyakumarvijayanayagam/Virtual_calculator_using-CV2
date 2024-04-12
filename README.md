# Scientific Virtual Calculator 

## Description
This project implements a scientific calculator using Python and various libraries such as OpenCV, Mediapipe, and CVZone. The calculator supports basic arithmetic operations along with advanced functions such as trigonometric, logarithmic, exponential, factorial, and more. Additionally, it provides a feature to calculate derivatives, combinations, and nth roots.

## Features
- Basic arithmetic operations: addition, subtraction, multiplication, division.
- Trigonometric functions: sine, cosine, tangent.
- Logarithmic functions: natural logarithm (ln) and base-10 logarithm (log).
- Exponential function (exp).
- Factorial (fact) and square root (sqrt) functions.
- Derivative calculation (der).
- Combinations (ncr) and nth root (nrt).
- Hypotenuse calculation (hyp).
- Supports input using hand gestures detected via webcam.

## Dependencies
- Python 3.x
- OpenCV (`cv2`)
- Mediapipe (`mediapipe`)
- CVZone (`cvzone`)
- SymPy (`sympy`)

## Installation
1. Install Python from [python.org](https://www.python.org/).
2. Install required libraries using pip:
    ```
    pip install opencv-python mediapipe sympy
    pip install cvzone
    ```
3. Clone or download this repository.

## Usage
1. Run the `main.py` script using Python:
    ```
    python main.py
    ```
2. Position your hand in front of the webcam to interact with the calculator.
3. Use hand gestures to click on the buttons corresponding to the desired operations or input values.
4. The equation and results will be displayed on the screen.

## Hand Gestures
- To click a button, bring the index finger close to the thumb. A circular highlight will indicate the selected button.
- Use appropriate hand gestures to navigate through different functionalities.

## Notes
- Ensure proper lighting and hand visibility for accurate gesture detection.
- The calculator supports basic error handling but may not cover all edge cases.
- For complex equations or functions, ensure proper formatting and use parentheses where necessary.

## Contributors
Suriyakumar Vijayanayagam

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
- Thanks to the creators of OpenCV, Mediapipe, and CVZone for their invaluable tools and documentation.
