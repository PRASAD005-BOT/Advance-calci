🌟 Gemini Matrix Solver

A Flask web application that leverages Google’s Gemini model to process matrix images and provide detailed solutions. Users can upload images of matrix problems, and the application will return a detailed solution and explanation.

 🚀 Features

- **Matrix Problem Solver**: Upload a matrix image, and the AI generates a solution with an explanation.
- **Flask Integration**: Uses Flask to handle file uploads and render templates.
- **Google Generative AI API**: Processes images and text prompts to return detailed responses.
- **Secure Uploads**: Images are securely saved and processed within the static folder.
- **User-Friendly Interface**: Clean, intuitive UI for easy interaction.

 📚 Getting Started

 Prerequisites

- Python **3.7 or higher
- Flask
- Google Generative AI SDK
- `dotenv` for environment variable management
- `Werkzeug` for handling file security

Install required packages:

bash
Copy code
pip install -r requirements.txt
Set up environment variables:

Create a .env file in the root directory.
Add your Google API Key:
plaintext
Copy code
GOOGLE_API_KEY=your_api_key_here
Run the application:

bash
Copy code
python app.py
Access the application in your browser at http://127.0.0.1:5000.

Usage
Navigate to the homepage.
Upload a matrix image in the designated form.
Submit the image, and the model will process the matrix problem, returning a solution with a detailed explanation.
🔗 Links
Live Website: Gemini Matrix Solver
Demo Video: YouTube
📂 File Structure
plaintext
Copy code
├── app.py                # Main Flask application
├── templates/
│   └── index.html        # Homepage HTML file
├── static/               # Folder for uploaded images
└── README.md             # Project documentation
📝 License
This project is licensed under the MIT License. All rights are reserved by PrasadEngineer.

🌟 Support
If you find this project useful, please give it a star! ⭐

This project was developed using Flask, Python, and Google Generative AI.

