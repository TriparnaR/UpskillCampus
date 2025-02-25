# UpskillCampus
The project that we have created is:  

---

# Crop & Weed Detection Using YOLOv8 🌱  

## Overview  
This project is a **Streamlit-based web application** that uses **YOLOv8** for **crop and weed detection** from images. It includes **user authentication** and allows users to upload images for plant analysis.  

## Features  
✅ **User Authentication** (Login/Register)  
✅ **Crop & Weed Detection** using **YOLOv8**  
✅ **Streamlit Web Interface** for easy interaction  
✅ **Database (SQLite)** for storing user credentials  

## Installation  

1️⃣ **Clone the repository**  
```bash
git clone <repository-url>
cd Crop-Weed-Detection
```

2️⃣ **Install dependencies**  
```bash
pip install -r requirements.txt
```

3️⃣ **Download YOLOv8 model weights** (Replace with correct path)  
```bash
mv best.pt path/to/model/best.pt
```

4️⃣ **Run the application**  
```bash
streamlit run Crop&WeedDectionUsingYOLOv8.py
```

## Requirements  
- **Python 3.x**  
- **YOLOv8 (Ultralytics)**  
- **Streamlit**  
- **SQLite3**  
- **PIL (Pillow)**  
- **OS & Asyncio**  

## How It Works  
1️⃣ **User Registration/Login**  
2️⃣ **Upload an Image** (Crop/Weed Image)  
3️⃣ **YOLOv8 Model Processes the Image**  
4️⃣ **Detection Results Displayed**  

## Folder Structure  
```
📂 Crop-Weed-Detection  
 ├── 📜 Crop&WeedDectionUsingYOLOv8.py  # Main Streamlit app  
 ├── 📜 best.pt                         # YOLOv8 Model weights  
 ├── 📜 users.db                        # SQLite database  
 ├── 📂 runs                             # YOLOv8 results folder  
 ├── 📂 assets                           # Background images & UI assets  
 ├── 📜 requirements.txt                 # Dependencies  
 ├── 📜 README.md                        # Project Documentation  
```

## Future Improvements  
🔹 Improve UI/UX with **better visualization**  
🔹 Enhance **model accuracy** by training on a larger dataset  
🔹 Implement **role-based access control**  

## Author  
🚀 Developed by **Triparna Roy** and **Rishika S** 

## License  
📝 This project is **open-source** and available under the **MIT License**  

---
