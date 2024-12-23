# AI Shield: Integrated Distress Monitoring and Alert System

## Project Overview
**AI Shield** is an advanced AI-based safety alert system designed to enhance personal security, particularly for women. The system detects distress signals, such as scream audio, and automatically alerts trusted contacts with the GPS coordinates of the location. By leveraging machine learning and audio processing, AI Shield provides a proactive and reliable safety mechanism. It also has the potential for future integration with biometric and wearable technologies for enhanced safety.

---

## Features
- **Real-Time Distress Detection:** Detect scream audio and abnormal physiological patterns (e.g., pulse and heart rate) in real time.
- **Automated Alerts:** Share GPS coordinates with trusted contacts when distress is detected.
- **User-Friendly Interface:** Intuitive app design for easy use.
- **Future Integration:** Support for wearable accessories and biometric data.

---

## Setup Instructions

### Step 1: Clone the Repository
```bash
git clone https://github.com/your-repository/ai-shield.git
cd ai-shield
```

### Step 2: Install Dependencies
Ensure you have Python 3.7+ installed. Install required dependencies using:
```bash
pip install -r requirements.txt
```

### Step 3: Download Pre-trained Models
Download the pre-trained AI model for audio classification from [Google Drive/Cloud](#link) and place it in the `models` directory.

### Step 4: Set Up API Keys
- Obtain an API key for **Google Maps** (for GPS coordinates) and configure it in `config.py`.
- Set up your SMS or email notification service credentials in `config.py`.

### Step 5: Run the Application
Launch the app with:
```bash
python app.py
```

---

## Dependencies List
- Python 3.7+
- Flask (for web interface)
- TensorFlow or PyTorch (for AI model)
- Numpy, Pandas (data processing)
- Librosa (audio processing)
- Matplotlib/Seaborn (visualizations)
- Twilio or SendGrid (notifications)
- OpenCV (for multimodal extensions)
- Google Maps API

---

## Usage Examples
1. **Launching the App**  
   Run the app and access the user interface at `http://localhost:5000`.

2. **Detecting Distress Signals**  
   - Speak or scream into the app's microphone input.
   - If distress is detected, the system will:
     - Notify trusted contacts via SMS/email.
     - Share the user’s GPS location.

3. **Configuring Trusted Contacts**  
   Add and manage trusted contacts through the app interface.

---

## Screenshots/GIFs
### App Dashboard  
![App Dashboard](screenshots/dashboard.png)

### Detection in Action  
![Detection Example](screenshots/detection.gif)

---

## Team Members
- **Subhash**  
  - **Role:** Developer and Project Lead  
  - **Expertise:** AI/ML, Audio Processing, Python Development, Data Analysis  
  - **Contact:** [Email](mailto:subhash@example.com)

---

## Future Enhancements
- Integration with wearable accessories like censored rings, bangles, earrings, and GPS-enabled clothing.
- Multimodal distress detection combining audio, video, and biometric data.
- Localization with support for multiple languages and region-specific alert systems.

---

## License
This project is licensed under the [MIT License](LICENSE).

---

## Contributions
Contributions are welcome! Please fork the repository and submit a pull request for review.

---

## Contact
For any queries or suggestions, please contact Subhash at [subhash@example.com](mailto:subhash@example.com).
