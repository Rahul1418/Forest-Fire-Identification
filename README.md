# 🌲🔥 Forest Fire Identification Method for UAV Monitoring

## 📜 Overview
This project focuses on identifying forest fires from UAV (Unmanned Aerial Vehicle) video footage. The proposed method applies several techniques to detect and identify fire or smoke. 

## 🔍 Techniques Used
1. **Image Processing**: 
   - Reads video frame by frame.
   - Converts BGR image format to RGB format for analysis.
   
2. **Motion Detection**:
   - Utilizes Python OpenCV to detect movement in the video.
   - Extracts moving areas if the movement angle is between 0-90 degrees.

3. **Colour Features Extraction**:
   - Extracts color features related to fire.
   - Helps in detecting fire or smoke based on color analysis.

4. **Wavelet and Texture Extraction**:
   - Extracts wavelet and texture features.
   - Determines whether the color features indicate fire.
   - Outputs a “fire detected” result if fire is identified.

## 💻 Getting Started

1. **Run the Application**:
   - Double-click on `run.bat` file to start the application.

2. **Upload Video**:
   - Click on the **‘Upload UAV Forest Fire Video’** button to upload your video.

3. **Processing**:
   - After uploading, click the **‘Open’** button to load the video.
   - Then click on **‘Run Motion Detection, Colour Features and Wavelet Transform to Detect Fire’** to start processing.

4. **Results**:
   - If no fire is detected, the screen will show no fire movement.
   - If fire is detected, the output will display the detected fire with movement shown in a black window.

## 🖼️ Screenshots

### Initial Screen
- ![Initial Screen](path/to/screenshot1.png)
- **Action**: Click on ‘Upload UAV Forest Fire Video’.

### Video Upload
- ![Video Upload](path/to/screenshot2.png)
- **Action**: Select and upload your video, then click ‘Open’.

### Processing and Detection
- ![Processing](path/to/screenshot3.png)
- **No Fire Detected**: Black screen with no fire movement.

- ![Fire Detected](path/to/screenshot4.png)
- **Fire Detected**: Movement and fire detection shown in the black window.

## ⚙️ Technologies
- **Programming Language**: Python
- **Libraries**: OpenCV, NumPy

## 📩 Contact
- For any questions or feedback, please reach out to [your.email@example.com](mailto:your.email@example.com).

## 📄 License
- This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
