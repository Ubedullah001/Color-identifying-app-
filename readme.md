Color Match & Identifier
A simple Streamlit web application for identifying and matching colors from color-code values.
Features
Enter a HEX color code.
Enter RGB values.
Preview the selected color.
Display HEX, RGB, and HSL values.
Give a simple color-category description.
Generate:
Complementary colors
Analogous colors
Triadic colors
Simple interface suitable for a student academic project.
Files
App.py — main Streamlit application.
requirements.txt — required Python package.
README.md — project documentation.
Run locally
Install Python 3.10 or newer.
Open a terminal in this project folder.
Install the requirements:
pip install -r requirements.txt
Start the application:
streamlit run App.py
Open the local URL shown by Streamlit, normally:
http://localhost:8501
GitHub
Create a GitHub repository and upload these three files:
Color-Match-Identifier/
├── App.py
├── requirements.txt
└── README.md
Deployment
The project can be deployed using a Streamlit-compatible hosting service connected to the GitHub repository.
Project purpose
This is an academic prototype demonstrating how color-code values can be converted into useful color information and matching palettes. It can later be extended with image-based color detection, color-name databases, textile color matching, saved palettes, and accessibility/contrast analysis.
