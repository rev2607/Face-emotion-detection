# 🚀 Face Emotion Detection & Engagement Analyzer
> An intelligent computer vision system that automatically detects human emotions from images and calculates audience engagement levels for presentations, meetings, and events.

![Tech Stack](https://img.shields.io/badge/Tech-Python|OpenCV|FER|MTCNN-blue)

## 📌 Overview
This project is a sophisticated **Face Emotion Detection and Engagement Analyzer** that leverages advanced computer vision and machine learning techniques to:

- **Automatically detect faces** in images using MTCNN (Multi-task Cascaded Convolutional Networks)
- **Analyze facial expressions** to identify 7 primary emotions (happy, sad, angry, fear, disgust, surprise, neutral)
- **Calculate engagement metrics** by categorizing emotions as engaged vs. disengaged
- **Provide real-time insights** for audience analysis in presentations, classrooms, and events

**Why it's useful**: Traditional audience engagement measurement relies on manual observation or expensive equipment. This solution provides instant, accurate, and scalable emotion analysis using just a camera or image.

**Who it's for**: 
- 🎓 Educators and trainers monitoring student engagement
- 🏢 Business professionals analyzing meeting participation
- 🎭 Event organizers measuring audience reactions
- 📊 Researchers studying human behavior and emotions

## ✨ Features
- ✅ **Multi-Face Detection** - Automatically identifies all faces in an image
- ✅ **7-Emotion Classification** - Recognizes happy, sad, angry, fear, disgust, surprise, neutral
- ✅ **Engagement Scoring** - Categorizes emotions into engaged vs. disengaged groups
- ✅ **Real-time Analysis** - Processes images instantly with bounding box visualization
- ✅ **Percentage Metrics** - Provides detailed engagement statistics and overall status
- ✅ **Professional Output** - Generates clean, annotated images with emotion labels

## 🖼️ Demo
The system processes input images and outputs annotated versions with:
- Green bounding boxes around detected faces
- Emotion labels with confidence scores above each face
- Console output showing engagement statistics

**Input**: Any image containing human faces  
**Output**: Annotated image with emotion detection + engagement analysis

## ⚙️ Tech Stack
- **Languages**: Python 3.10+
- **Frameworks**: 
  - OpenCV (cv2) for image processing
  - FER (Facial Emotion Recognition) for emotion detection
  - MTCNN for face detection
- **Tools**: 
  - Google Colab for development and testing
  - Jupyter Notebook for interactive development

## 🚀 Getting Started

### ✅ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/rev2607/Face-emotion-detection.git
   cd Face-emotion-detection
   ```

2. **Install dependencies**
   ```bash
   pip install fer opencv-contrib-python
   ```

3. **Run the notebook**
   ```bash
   jupyter notebook face_detection.ipynb
   ```

4. **Upload your image** and update the `image_path` variable

5. **Execute cells** to analyze emotions and get engagement metrics

### 📂 Project Structure
```
Face-emotion-detection/
├── face_detection.ipynb    # Main emotion detection notebook
├── README.md               # Project documentation
└── .git/                   # Version control
```

### 📈 Output
The system provides comprehensive analysis including:
- **Face Detection**: Bounding boxes around all detected faces
- **Emotion Labels**: Dominant emotion with confidence score for each person
- **Engagement Metrics**: 
  - Number of engaged individuals (happy, neutral, surprise)
  - Number of disengaged individuals (sad, angry, fear, disgust)
  - Percentage breakdowns
  - Overall engagement status (Highly/Moderately Engaged or Disengaged)

### 🛠️ Use Cases
- **Educational Settings**: Monitor student engagement during lectures
- **Business Meetings**: Analyze participant attention and interest levels
- **Event Management**: Measure audience reactions to presentations
- **Research Studies**: Collect emotion data for behavioral analysis
- **Customer Experience**: Analyze customer reactions to products/services

## 🚀 Future Enhancements
- Real-time video processing capabilities
- Web application interface
- API endpoints for integration
- Advanced analytics dashboard
- Multi-language support

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License
This project is open source and available under the [MIT License](LICENSE).

---

## 🙌 Author

**Revanth Guthula**
- 📧 Email: [revanthg2607@gmail.com](mailto:revanthg2607@gmail.com)
- 🔗 LinkedIn: [rev2607](https://linkedin.com/in/rev2607)
- 🌐 Portfolio: [www.revanth.cloud](https://www.revanth.cloud)
- 🐙 GitHub: [@rev2607](https://github.com/rev2607)

---

<div align="center">
  <p>⭐ Star this repository if you find it helpful!</p>
  <p>Made with ❤️ by Revanth Guthula</p>
</div>
