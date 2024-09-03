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

![image](https://github.com/user-attachments/assets/4b7716b8-338d-4e87-b72a-73171de05385)
![image](https://github.com/user-attachments/assets/794a89fe-0ad2-46b5-acfa-aedaa614c734)
![image](https://github.com/user-attachments/assets/3afce7a2-fe27-48eb-a28d-77759997a2c5)
![image](https://github.com/user-attachments/assets/5b0cefbb-b885-40c8-b2f2-bbaf70a2c059)
![image](https://github.com/user-attachments/assets/2a0f8619-4b8c-4567-817d-9f9ef2046337)
![image](https://github.com/user-attachments/assets/f407e75c-b623-427c-b3d6-a13d8c8cb90b)
![image](https://github.com/user-attachments/assets/1b589875-2929-4806-a0c7-09e281bad645)
![image](https://github.com/user-attachments/assets/6eb8ab77-ad18-4b89-a18d-328a0c4c9f57)

## ⚙️ Technologies
- **Programming Language**: Python
- **Libraries**: OpenCV, NumPy

## 📩 Contact
- For any questions or feedback, please reach out to [your.email@example.com](mailto:your.email@example.com).

## 📄 License
- This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
