# Literature Survey

---

# A. Civic Issue Management Systems

---

## 1. Smart Civic Issue Reporting System

**Source:** International Journal of Advanced Research in Science, Communication and Technology (IJARSCT), 2022  
**DOI:** [https://doi.org/10.48175/IJARSCT-2659](https://doi.org/10.48175/IJARSCT-2659)  
**File Reference:** Civicissues  

### Objective

The objective of this paper is to develop a smart Android-based civic complaint reporting system that enables citizens to report infrastructure issues such as potholes, garbage overflow, streetlight damage, and road defects in an efficient and structured manner.

### Methodology

The proposed system uses a hybrid CNN-RNN image processing algorithm along with an SVM-NLP model to detect and classify reported issues.

Severity detection is automatically performed so that high-priority complaints are addressed first.

GPS sensors are integrated to ensure accurate geo-location tracking, and mobile cameras capture visual evidence.

The system follows a three-tier client-server architecture based on the MVC design pattern.

### Key Features

- Android-based complaint submission  
- GPS-based geo-tagging  
- Hybrid CNN-RNN model for image processing  
- SVM-based NLP for severity detection  
- Automated routing to relevant authorities  

### Limitations

- Focused only on civic complaint reporting  
- Requires high-quality image input  
- No advanced predictive analytics or dashboard  

### Relevance to Our Project

This paper supports the civic issue detection component of our system.

Our project enhances this approach by integrating traffic density monitoring and AI-based automation into a unified smart urban management framework.

---

## 2. Digital Grievance Redressal for Cleaner, Smarter India

**Source:** International Journal of Computer Techniques, Volume 12, Issue 3, May–June 2025  
**Link:** [https://ijctjournal.org/](https://ijctjournal.org/)  
**File Reference:** DIGITAL GRIEVANCE REDRESSAL FOR CLEANER, SMARTER INDIA  

### Objective

This research proposes a centralized digital grievance redressal platform aimed at improving transparency, efficiency, and accountability in urban governance using AI and NLP techniques.

### Methodology

The system follows a multi-layer architecture including:

- User Interface Layer (React/Next.js)  
- Middleware Layer  
- Backend Layer (Node.js/Express)  
- Database Layer (MongoDB)  
- Analytics & Admin Dashboard Layer  

Natural Language Processing (NLP) is used for complaint categorization, while Machine Learning models are applied for urgency-based prioritization.

The system includes tracking, escalation workflows, and analytics dashboards.

### Key Features

- Web and Mobile complaint submission  
- AI-based complaint classification  
- Urgency prediction mechanism  
- Real-time tracking and notifications  
- Escalation management system  
- Administrative analytics dashboard  

### Limitations

- Focuses mainly on text-based complaints  
- Does not include deep image-based detection  
- No traffic management integration  

### Relevance to Our Project

This paper provides a strong digital governance framework.

Our project builds upon it by incorporating computer vision for automated civic issue detection and integrating traffic density analysis for intelligent decision support.

---

## 3. Smart Civic Issue Reporting System (Crowdsourced Model)

**Source:** IJARSCT, Volume 2, Issue 1, March 2022  
**DOI:** [https://doi.org/10.48175/IJARSCT-2659](https://doi.org/10.48175/IJARSCT-2659)  
**File Reference:** Paper2659 (1)  

### Objective

The paper aims to maximize crowdsourcing potential through a smartphone-based civic complaint system to improve communication between citizens and government authorities.

### Methodology

The system uses:

- Android mobile application  
- Three-tier client-server architecture  
- MVC design pattern  
- GPS-based location tagging  
- Image evidence submission  
- Centralized server notification system  

The architecture includes user, official, and admin modules.

### Key Features

- Two-click complaint submission  
- Location-based complaint routing  
- Real-time status tracking  
- Administrative backend management  

### Limitations

- Limited AI-based automation  
- Focuses primarily on complaint reporting  
- No predictive analytics integration  

### Relevance to Our Project

This study validates the importance of geo-tagged mobile-based civic reporting.

Our system advances this model by incorporating AI-driven detection and integrating traffic density-based management.

---

# B. Traffic Density Management Systems

---

## 4. Video-Based Traffic Density Calculator with Traffic Light Control Simulation

**Source:** AIP Conference Proceedings, 2020  
**DOI:** [https://doi.org/10.1063/5.0026154](https://doi.org/10.1063/5.0026154)  
**File Reference:** 020046_1_online  

### Objective

The objective of this study is to calculate traffic density using image processing techniques and simulate traffic signal control based on congestion levels.

### Methodology

CCTV footage from road intersections is processed using the Haar-Cascade algorithm for vehicle detection.

Traffic density is classified into:

- Low  
- Moderate  
- Heavy  

Traffic signal timing is adjusted according to detected density levels.

### Results

The system achieved approximately 80% vehicle detection accuracy and successfully demonstrated density-based traffic light simulation.

### Limitations

- Uses traditional Haar-Cascade detection  
- Reduced accuracy under occlusion or poor lighting  
- Limited scalability  

### Relevance to Our Project

This paper provides a foundational understanding of density-based traffic control.

Our project improves this method by using deep learning-based YOLO detection for higher accuracy and real-time deployment.

---

## 5. Intelligent Traffic-Monitoring System Based on YOLO and Convolutional Fuzzy Neural Networks

**Source:** IEEE Access, 2022  
**DOI:** [https://doi.org/10.1109/ACCESS.2022.3147866](https://doi.org/10.1109/ACCESS.2022.3147866)  
**File Reference:** Intelligent_Traffic-Monitoring_System  

### Objective

This paper proposes a real-time traffic monitoring system using deep learning techniques for vehicle detection and classification.

### Methodology

YOLO is used for vehicle detection, while a Convolutional Fuzzy Neural Network (CFNN) is integrated for classification.

The system processes real-time video streams to count vehicles and estimate traffic flow.

### Results

The system achieved over 90% detection accuracy and operated at more than 30 frames per second, making it suitable for real-time applications.

### Limitations

- Requires large training datasets  
- Computationally intensive  
- Does not include signal optimization  

### Relevance to Our Project

This research directly supports our traffic density estimation module.

We adopt YOLO-based vehicle detection to classify congestion levels and enable smart traffic decision-making.

---

## 6. An Improved YOLO-Based Road Traffic Monitoring System

**Source:** Springer – Computing Journal, 2021  
**DOI:** [https://doi.org/10.1007/s00607-020-00869-8](https://doi.org/10.1007/s00607-020-00869-8)  
**File Reference:** Improved YOLO-Based Traffic Monitoring  

### Objective

The study proposes an enhanced YOLO-based system for vehicle detection, tracking, and counting in real-world traffic scenarios.

### Methodology

YOLOv3 is combined with tracking mechanisms to detect and track vehicles across frames.

The system handles variations in camera angles and environmental conditions.

### Results

The system demonstrated robust performance under dynamic traffic conditions and improved accuracy in vehicle tracking.

### Limitations

- Focused solely on traffic monitoring  
- Requires GPU for optimal performance  

### Relevance to Our Project

This paper supports the implementation of YOLO for accurate vehicle detection.

Our system extends this approach by integrating civic issue detection and automated complaint management.
