# Automatic Car License Plate Detection

This project implements automatic car license plate detection using YOLO v9, and trained on a custom dataset obtained from Kaggle. It utilizes pytesseract for Optical Character Recognition (OCR) to extract license plate numbers from detected plates. The application is deployed using Streamlit for easy user interaction.

## Features

- **Upload Media:** Allows users to upload images or videos for license plate detection.
- **Real-time Processing:** Capable of processing both images and videos, displaying results promptly.
- **License Plate Recognition:** Detects license plates in uploaded media and extracts alphanumeric characters using pytesseract.
- **Output Visualization:** Displays annotated images or processed videos with bounding boxes around detected license plates and recognized text overlay.

## Installation
1. Clone the repository:

   ```bash
   git clone https://github.com/AbdurRahman22224/YOLO-Car-License-Plate-Detection
   cd YOLO-Car-License-Plate-Detection
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

   Make sure to have the necessary versions of Python and CUDA installed if using GPU. (my output is cpu based)

3. Run the Streamlit app:

   ```bash
   streamlit run app.py
   ```

   Replace `app.py` with the name of your Streamlit application script.

## Usage

- Access the Streamlit web interface locally or on a server where the app is deployed.
- Upload an image or video file containing cars with visible license plates.
- Click "Proceed" to start processing.
- The application will display the processed media with annotated license plates.

## Dependencies

- **YOLOv8:** Utilized for object detection and localization.
- **PyTesseract:** For OCR to extract text from license plate regions.
  - **Streamlit:** Framework for deploying and interacting with machine learning applications.
- **OpenCV:** Image and video processing library used for loading, processing, and saving media files.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request for any improvements or additional features.
## Acknowledgments

- **Ultralytics YOLO:** For providing a powerful YOLO implementation.
- **Kaggle:** For the dataset used for training.
- **Streamlit Community:** For the intuitive framework for deploying ML applications.

## Contact

For questions or support regarding this project, please contact [Samarth Solanki](samarthsolanki56@gmail.com).
