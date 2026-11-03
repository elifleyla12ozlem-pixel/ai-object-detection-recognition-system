AI Object Detection & Recogniton System

Overwiew

An AI powered computer vision application that detects and recognizes objects in images using the YOLO11
deep learning model. The system proceses uploaded images, idenfities objects, displays bounding boxes with confidence scores and generates 
dowlodable detection reports.

Features

- Real-time image-based object detection
- Object recognition using the pretrained YOLO11n model
- Bounding box visualization with confidence scores
- Detection results displayed in an interactive table
- Automatic object dtection reports
- CSV report generation and download
- Interactive web interface built with Gradio

  Technologies Used

  - Python
  - YOLO11 (Ultralytics)
  - OpenCV
  - Gradio
  - Pandas
  - Google Colab
 
  How It Works

  1. The user uploads an image.
  2. The YOLO11 model analyzes the image.
  3. Detected objects are identified and classified.
  4. Bounding boxes and confidence scores are displayed.
  5. Detection results are presented in a structured table.
  6. A CSV report is generated for download.
 
  Project Structure

  ai-object-detection-recognition-system
    notebooks
      ai-object-detection.ipynb
    screenshots
    Readme.md
    reguirements.txt
    .gittignore

  Getting Started

  1. Open the Jupyter Notebook in Google Colab.
  2. Install the required dependencies.
  3. Load the pretrained YOLO11 model.
  4. Update an image.
  5. Run the detection process .
  6. View the results and download the CSV report.
 
  Application Interface

  The project includes an interactive Gradio interface where users can upload images,
  view detected objects, examine confidence scores, and download detection reports.

  Future Improvements

  - Custom model training
  - Improved detection accuracy
  - Video-based object detectiiion
  - Integration with robotic systems
 
    Author
    Elif Özdilek

    Mechatronics Technician - AI & Computer Visuan Enthusiasist

  
