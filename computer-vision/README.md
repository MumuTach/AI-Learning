# 🧠 Image Analysis with Azure AI Vision – Personal Learning Project

This project is a **hands-on AI learning project** that I completed to deepen my understanding of **computer vision and artificial intelligence using Microsoft Azure**.

Through this project, I explored how pre-built AI models can analyze images, generate descriptions, detect objects, and identify people. It reflects my strong interest in AI technologies and my motivation to learn by building and experimenting with real cloud-based solutions.

---

## 🎯 Project Objective

The goal of this project was to **understand how AI systems interpret visual data** by:

* Provisioning an Azure AI Vision resource
* Connecting securely to Azure AI services
* Using the Azure AI Vision SDK in Python
* Implementing multiple computer vision features step by step
* Interpreting AI confidence scores and results

This project is based on a Microsoft Learn lab, but all configuration, setup, execution, and code integration were performed by me.

---

## 🧩 What I Implemented

I personally implemented and tested the following AI features:

* ✅ Image caption generation
* ✅ Dense captions for detailed scene understanding
* ✅ Automatic tag extraction
* ✅ Object detection with bounding boxes
* ✅ People detection with confidence filtering
* ✅ Image annotation and result visualization

Each feature was added incrementally to better understand how the AI model responds to different visual inputs.

---

## 🛠️ Technologies & Tools Used

* **Python**
* **Azure AI Vision (Computer Vision)**
* **Azure AI Vision Python SDK**
* **Azure Cloud Shell**
* **Git & GitHub**
* **Virtual environments (venv)**

---

## ☁️ Azure Setup (What I Did)

1. Created a **standalone Azure AI Vision (Computer Vision)** resource
2. Selected the **Free (F0) pricing tier** for experimentation
3. Retrieved the **endpoint and API key** from the Azure Portal
4. Configured secure environment variables using a `.env` file
5. Connected my Python application to Azure AI Vision using authenticated SDK access

This helped me understand how cloud-based AI services are securely consumed by client applications.

---

## ⚙️ Local Project Setup

Clone the repository:

```bash
git clone https://github.com/MicrosoftLearning/mslearn-ai-vision
cd mslearn-ai-vision/Labfiles/analyze-images/python/image-analysis
```

Create and activate a virtual environment:

```bash
python -m venv labenv
./labenv/bin/Activate.ps1
```

Install dependencies:

```bash
pip install -r requirements.txt azure-ai-vision-imageanalysis==1.0.0
```

---

## 🔐 Configuration

I configured the application using environment variables:

```env
AI_ENDPOINT=https://<your-resource-name>.cognitiveservices.azure.com/
AI_KEY=your_api_key_here
```

---

## ▶️ Running the Application

I tested the application using multiple images to observe how AI outputs vary depending on content:

```bash
python image-analysis.py images/street.jpg
python image-analysis.py images/building.jpg
python image-analysis.py images/person.jpg
```

---

## 📊 Observed Results

* AI-generated captions with confidence scores
* Relevant tags describing image content
* Detected objects with bounding boxes (`objects.jpg`)
* Detected people with location data and confidence thresholds (`people.jpg`)
* Visual understanding differences between urban scenes, buildings, and people

This experimentation helped me better understand **model confidence, limitations, and interpretation of results**.

---

## 🧠 What I Learned

* How AI vision models analyze visual features
* How to work with cloud-based AI services
* How to authenticate and consume Azure AI APIs
* How to interpret AI confidence scores
* How to structure an AI project for experimentation and learning

This project reinforced my interest in **artificial intelligence and applied machine learning**, particularly in computer vision.

---

## 📚 References

* Microsoft Learn – Analyze images with Azure AI Vision
* Azure AI Vision Documentation
