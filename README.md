# Nutri Check App

## Overview
The Nutri Check App leverages advanced AI technology to enable users to analyze the nutritional content of their meals by simply uploading images. This application aims to assist users in maintaining a balanced diet by providing detailed insights into calorie counts and nutritional information.

## YouTube Tutorial
Watch our [detailed tutorial on YouTube](#) to get started and learn how to use all the features of the Gemini Health App effectively.

## Key Features
- **Nutritional Analysis:** Utilizes AI to identify food items in images and quantifies total calories along with a breakdown of proteins, carbohydrates, and fats.
- **Health Tracking:** Helps users monitor their diet by providing feedback on the healthiness of their meals and suggesting nutritional adjustments.

## Technology Stack
- **Streamlit:** Creates a user-friendly web interface.
- **Pillow (PIL):** Manages image processing tasks.
- **dotenv:** Handles environment variable management.
- **Google Generative AI:** Powers the backend AI model to generate detailed nutritional insights from food images.

## Setup and Installation

### Prerequisites
- Python 3.8 or higher
- Anaconda (recommended for environment management)

### Installation Steps
1. **Clone the Repository:**
   ```cmd
   git clone <repository-url>

2. **Open the Cloned Folder in Visual Studio Code**
   
   Navigate to the project directory in VS Code.

4. **Set Up Conda Environment:**
   ```
   conda create -n ven python=3.12.4 -y
   
   conda activate venv

4. **Create a .env File:**

   Inside your project directory, create a .env file to store your GOOGLE_API_KEY.

6. **Create Requirements File:**

   Create a requirements.txt file to list all necessary Python packages.

7. **Install Required Packages:**
  ```cmd
     pip install -r requirements.txt
```  

8. **Create the Streamlit App File:**
   `
   Ensure app.py is set up and ready by this step as the dependencies are installed. You can also use app.py from cloned repository directly.

9. **Run the Application**
   ```
   streamlit run app.py

## Usage Instructions
Navigate to the App
Begin by uploading an image of your food.
Provide any specific dietary needs or additional information in the designated area.
Submit for Analysis
The AI will analyze the image and present a detailed report on the nutritional content, assessing the healthiness of the food based on its nutrient profile.

## How AI Helps in Health Management
AI enhances our ability to understand and manage our health through advanced image recognition and data analysis techniques. This application processes visual and textual data to deliver precise nutritional information, enabling users to make informed decisions about their diets and overall health.

## Contributions
Contributions to the Gemini Health App are welcome. Please ensure to follow best practices for code style and updates.




  










  







