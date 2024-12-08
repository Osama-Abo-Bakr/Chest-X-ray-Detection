# Chest X-ray Detection 🫁  

This project is a **Chest X-ray Detection** web application developed using **Streamlit** and **YOLO**. The app allows users to upload chest X-ray images and performs real-time predictions using a pre-trained YOLO model. The result includes the predicted label and the associated probability.

---

## Features
- **Upload & Predict**: Upload X-ray images in `jpg`, `png`, or `jpeg` formats.
- **Model Predictions**: Detect chest conditions with YOLO and display the prediction with confidence.
- **Interactive Interface**: Built using Streamlit for an intuitive and user-friendly experience.

---

## Installation Instructions  

Follow these steps to set up the project on your local machine:

### Prerequisites
Ensure you have the following installed:
- Python 3.11 or later
- pip (Python package manager)

### Steps
1. **Clone the Repository**  
   Download or clone the project repository:
   ```bash
   git clone https://github.com/Osama-Abo-Bakr/Chest-X-ray-Detection.git
   cd Chest-Xray-Detection
   ```

2. **Create a Virtual Environment (Optional but Recommended)**  
   Set up a virtual environment to isolate project dependencies:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. **Install Dependencies**  
   Install the required Python packages using pip:
   ```bash
   pip install -r requirements.txt
   ```

4. **Download the Model**  
   Ensure the YOLO model file (`model_yolo-v1.pt`) is placed in the `models/` directory. If the directory or model file is missing, create the folder and download the model.

   ```bash
   mkdir -p models
   # Place your YOLO model file in the models directory
   ```

5. **Run the Application**  
   Launch the Streamlit app:
   ```bash
   streamlit run main.py
   ```

6. **Access the Application**  
   Open the URL shown in the terminal (usually `http://localhost:8501`) to access the app.

---

## File Structure  
```
Chest-Xray-Detection/
│
├── main.py               # Main application file
├── models/
│   └── model_yolo-v1.pt  # YOLO model file
├── requirements.txt      # Required Python packages
└── README.md             # Project documentation
```

---

## Requirements  

The project requires the following Python packages:
- **Streamlit**: `1.24.0`
- **Ultralytics**: `8.3.0`
- **NumPy**: `1.24.4`
- **Pillow**: `9.4.0`

Install all dependencies by running:
```bash
pip install -r requirements.txt
```

---

## Troubleshooting  

- **Image Upload Issues**: Ensure the uploaded file is in one of the supported formats (`jpg`, `png`, `jpeg`).  
- **Model File Missing**: Place the YOLO model file (`model_yolo-v1.pt`) in the `models/` directory.

---

## Contributing  

Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

Happy detecting! 🫁
