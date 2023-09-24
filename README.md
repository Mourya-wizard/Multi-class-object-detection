# Multi-class-object-detection-in-Satellite-imagery

This web application allows you to perform multiclass object detection in satellite imagery which is made using YOLOv8 and Streamlit. You can easily configure the model, select an image source, and visualize the detected objects.

## Features

- Select from multiple pre-configured models.
- Adjust model confidence threshold using a slider.
- Choose image source: upload your own or use a default image.
- Detect and visualize objects in the selected image.
- View detailed detection results in an expandable section.

## Installation

1. Clone this repository to your local machine:

   ```shell
   git clone https://github.com/your/repository.git
   cd repository-name
   ```

2. Install the required packages using pip:

   ```shell
   pip install -r requirements.txt
   ```

## Usage

1. Run the Streamlit app locally:

   ```shell
   streamlit run app.py
   ```

2. Open your web browser and navigate to the provided URL.

3. Use the sidebar to configure the model and select the image source.

4. Click the "Detect Objects" button to perform object detection.

5. View the detected objects in the image and explore detailed detection results.

## Configuration

- `settings.py`: Configure default settings, model paths, and image sources.
- Additional model configuration can be added as needed.

## Requirements

- Python 3.x
- Streamlit
- PIL (Python Imaging Library)

## Acknowledgments

This project is built using YOLOv8 and Streamlit, and we would like to acknowledge the contributions of the open-source community.
