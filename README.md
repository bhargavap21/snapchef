# SnapChef

A cutting-edge application that transforms your groceries into delicious recipes using AI-powered image recognition and recipe generation.

**SnapChef** utilizes state-of-the-art machine learning models to identify grocery items from images and recommend tailored recipes based on the available ingredients. Whether you're a culinary novice or a seasoned chef, SnapChef helps you reduce food waste and unleash your creativity in the kitchen.

![SnapChefDemo](https://github.com/user-attachments/assets/42c90b8b-5830-4485-bc43-4e26be8f52dc)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Installation

Install the package via pip:

```sh
pip install snapchef
```

## Features

* **AI-Powered Image Recognition**: Automatically identify groceries using advanced computer vision models.
* **Personalized Recipe Suggestions**: Get customized recipe recommendations based on your available ingredients.
* **Dietary Preferences**: Filters recipes to suit dietary restrictions like vegan, gluten-free, or low-carb.
* **Ingredient Optimization**: Maximizes the use of available ingredients to reduce food waste.

## Setup and Configuration

### Prerequisites

1. Python 3.8 or higher.
2. Required Python libraries listed in `requirements.txt`.
3. Access to Google Vision API for image recognition (optional but recommended).

### Installation Steps

1. Clone the repository:

```sh
git clone https://github.com/yourusername/SnapChef.git
```

2. Navigate to the project directory:

```sh
cd SnapChef
```

3. Install the required dependencies:

```sh
pip install -r requirements.txt
```

4. Set up the Google Vision API (optional):
   - Create a Google Cloud project.
   - Enable the Vision API.
   - Download the service account key JSON file and set the `GOOGLE_APPLICATION_CREDENTIALS` environment variable to its path.

## Usage Example

### Basic Usage

1. Launch the SnapChef app:

```sh
python snapchef.py
```

2. Upload a photo of your groceries.
3. View AI-generated recipe recommendations based on the identified ingredients.

### Command-Line Arguments

```sh
python snapchef.py --help
```

### Example Output

After uploading an image, the app processes the groceries and provides recipes like:

- **Recipe Name**: Spaghetti Carbonara
  - **Ingredients**: Pasta, eggs, pancetta, Parmesan cheese, pepper
  - **Preparation Time**: 20 minutes
  - **Instructions**: Follow step-by-step instructions in the app.

## Google Vision API Setup (Optional)

1. Go to the [Google Cloud Console](https://console.cloud.google.com/).
2. Create a new project and enable the Vision API.
3. Download the service account credentials and save the JSON file.
4. Set up the credentials in your environment:

```sh
export GOOGLE_APPLICATION_CREDENTIALS="/path/to/credentials.json"
```

## Template and Sample Recipes

SnapChef includes sample recipes and templates for testing. You can find these in the `recipes` folder.

### CSV Version:

A CSV file of sample recipes is available in the repository (`recipes.csv`) for offline use.

### How to Add Recipes:

1. Add new recipes to the `recipes.csv` file or use the in-app feature to save custom recipes.
2. Recipes will automatically sync the next time you launch the app.

## Development Setup

1. Clone the repository and navigate to the project directory.
2. Install the required dependencies using `requirements.txt`.
3. Run the application locally to test new features or debug issues.

## Disclaimer

If you encounter package compatibility issues, install dependencies in a local virtual environment:

```sh
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
```

## Meta

[Your Name] – [your-email@example.com]

Distributed under the MIT license. See `LICENSE` for more information.

[https://github.com/yourusername/SnapChef]
