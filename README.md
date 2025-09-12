Crop_CareAI
"AI-powered plant disease detection system for sustainable agriculture using deep learning and image classification."

GreenLeaf AI
MIT License Python Streamlit

GreenLeaf AI is a modern, web-based AI application that detects plant diseases from uploaded leaf images using a deep learning model. Built with Streamlit and TensorFlow/Keras, it provides instant diagnosis, confidence scores, and actionable recommendations for farmers, gardeners, and agricultural professionals.

Features
Upload plant leaf images (jpg/png/jpeg)
AI-powered disease detection using a trained TensorFlow/Keras model
Displays disease name, confidence score, and plant name
Treatment recommendations for diseased plants
Care tips for healthy plants
Modern, mobile-responsive UI inspired by SaaS products
Beautiful metrics, features, and results cards
Footer with contact info, social icons, and disclaimer
Fast, intuitive, and accessible
UI/UX Highlights
Fixed navbar with logo and tabs (Home, Disease Recognition, About)
Hero section with bold title, subtitle, and CTA
Metrics and features sections with clear layout
Card-based layout for results and recommendations
Responsive design for desktop and mobile
Soft green color palette (#1B5E20, #388E3C, #E8F5E9), rounded corners, and smooth shadows
Button and card hover animations
Placeholder image for uploads
Step-by-step flow for disease recognition
Demo
GreenLeaf AI Screenshot

Tech Stack
Frontend: Streamlit
Backend: TensorFlow Keras (pre-trained model)
Styling: Custom CSS
Python 3.7+
Folder Structure
Plant Disease Detection System for Sustainable Agriculture/
├── main.py                  # Main Streamlit app
├── requirements.txt         # Python dependencies
├── trained_plant_disease_model.keras  # Trained Keras model
├── training_hist.json       # Model training history
├── test/                    # Test images
├── README.md                # This file
├── ...                      # Other assets (notebooks, settings, etc.)
Model Information
Model: Convolutional Neural Network (CNN) trained on PlantVillage dataset
Input size: 128x128 pixels
Classes: 38+ plant disease/health classes
Supported plants: Apple, Tomato, Potato, Corn, Grape, Peach, Strawberry, Soybean, Raspberry, Blueberry, Cherry, Orange, Pepper, Squash
Accuracy: ~97% validation accuracy
File: trained_plant_disease_model.keras
Quickstart
Clone the repository:
git clone <your-repo-url>
cd "Plant Disease Detection System for Sustainable Agriculture"
(Optional) Create and activate a virtual environment:
python -m venv venv
venv\Scripts\activate  # On Windows
# Or: source venv/bin/activate  # On Mac/Linux
Install dependencies:
pip install -r requirements.txt
Run the app:
streamlit run main.py
Open in your browser:
Go to http://localhost:8501
Usage
Home: Learn about the app, see metrics and features
Disease Recognition: Upload a plant leaf image, click "Analyze Image" to get instant diagnosis and recommendations
About: See how the AI works, supported crops, and key features
Customization
Model: Replace trained_plant_disease_model.keras with your own Keras model (ensure input/output shape matches)
Styling: Edit CSS in main.py for color, spacing, or branding changes
Features: Add new pages, metrics, or features as needed
Images: Update placeholder or add your own icons in the assets folder
Troubleshooting
Model not found: Ensure trained_plant_disease_model.keras is in the project root
Dependency errors: Run pip install -r requirements.txt again
App not loading: Check for Python or Streamlit errors in the terminal
Image upload issues: Use clear, well-lit images in supported formats (jpg/png/jpeg)
Deployment
Streamlit Cloud
Push your code to GitHub.
Go to Streamlit Cloud and connect your repo.
Set the main file path to main.py and requirements to requirements.txt.
Deploy.
Heroku
Install Heroku CLI.
Add a Procfile with:
web: streamlit run main.py --server.port=$PORT
Push to Heroku and deploy as a Python app.
Advanced Usage
Retrain the Model:
Use the provided Jupyter notebooks or your own scripts to retrain on new data.
Save the new model as trained_plant_disease_model.keras.
Add New Classes:
Update the model and CLASS_NAMES in main.py.
UI Customization:
Edit the CSS in main.py for branding, layout, or color changes.
Contact & Support
Email: support@greenleafai.com
Twitter: @yourhandle
LinkedIn: GreenLeaf AI
For bugs or feature requests, please open an issue.
Issue & PR Templates
This repo supports GitHub issue and pull request templates for better collaboration.
See .github/ISSUE_TEMPLATE and .github/PULL_REQUEST_TEMPLATE (add these if missing).
Changelog
See CHANGELOG.md for release history and major updates.

Contributing
Fork the repo and create your branch: git checkout -b feature/your-feature
Commit your changes: git commit -am 'Add new feature'
Push to the branch: git push origin feature/your-feature
Open a pull request
Credits
UI/UX inspired by lovable.dev GreenLeaf AI project
PlantVillage dataset and open-source contributors
Streamlit and TensorFlow communities
License
This project is licensed under the MIT License. See LICENSE for details.
