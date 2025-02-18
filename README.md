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

## **📌 Project Impact**  
This project demonstrates the potential of **AI in healthcare**, improving **early cancer detection** and making medical information **more accessible** through an **interactive chatbot**.  

## **👥 Contributors**  
- **[Kareem Wael Elhamy](https://github.com/7ekmaz)** - [GitHub](https://github.com/7ekmaz) | [LinkedIn](https://www.linkedin.com/in/kareem-wael-k918/)  
- **[Azza Hassan Said](https://github.com/AzzaHassan17)** - [GitHub](https://github.com/AzzaHassan17) | [LinkedIn](https://www.linkedin.com/in/azza-hassan-40097a276)  
