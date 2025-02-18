# **AI-Powered Breast Cancer Detection & Q&A Chatbot**  

## **Overview**  
This project integrates **computer vision** and **natural language processing (NLP)** to enhance breast cancer detection and provide an interactive Q&A system for medical inquiries. The system consists of:  
- A **deep learning model** for breast cancer detection using medical images.  
- An **AI-powered Q&A chatbot** to assist users with relevant medical information.  
- **Multi-platform deployment** via **Flask** and **Streamlit** for accessibility.  

## **🔬 Breast Cancer Detection Using Computer Vision**  
- **First Approach (Custom Hybrid Model):**  
  - Built a custom deep learning model combining **EfficientNet, a CNN-based “neck” section, and a Vision Transformer-like module** for feature extraction.  
  - Designed to capture image features from multiple perspectives for classification.  
- **Second Approach (Xception – Higher Accuracy):**  
  - Transitioned to **Xception** after comparative analysis showed **higher accuracy and better generalization**.  
  - Implemented **transfer learning and fine-tuning** for optimized performance.  
- Preprocessed and augmented medical imaging data to improve model robustness.  
- Evaluated performance using **accuracy, precision, recall, and AUC-ROC metrics**.  

## **💬 AI Chatbot for Breast Cancer Q&A**  
- **First Approach:** Built a **custom transformer-based NLP model** before switching to **Hugging Face’s RoBERTa** for improved accuracy.  
- Integrated a **custom knowledge base** to enhance chatbot responses.  
- Added **multi-language support** using **Deep Translator**.  
- Deployed via **Flask** and **Streamlit**, providing a user-friendly web interface.  

## **🛠️ Technologies Used**  
- **Deep Learning:** TensorFlow, Keras (Custom Hybrid Model: EfficientNet + CNN + Vision Transformer, Xception)  
- **NLP & Chatbot:** Hugging Face RoBERTa, Custom Transformer, Deep Translator  
- **Data Processing:** OpenCV, Pandas, NumPy  
- **Web Deployment:** Flask, Streamlit  
- **Visualization & Analytics:** Power BI  

## **🚀 How to Run the Project**  

### **1. Clone the Repository**  
```bash
git clone https://github.com/yourusername/breast-cancer-detection-chatbot.git
cd breast-cancer-detection-chatbot
```

### **2. Install Dependencies**  
```bash
pip install -r requirements.txt
```

### **3. Run the Flask Server**  
```bash
python app.py
```

### **4. Run the Streamlit Interface (Optional)**  
```bash
streamlit run chatbot.py
```

## **📌 Project Impact**  
This project demonstrates the potential of **AI in healthcare**, improving **early cancer detection** and making medical information **more accessible** through an **interactive chatbot**.  
