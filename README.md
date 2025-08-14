# 🖼️ Build an image labels generator using Amazon Rekognition

This project uses **Amazon Rekognition** to detect and label objects in images automatically.  
Example: upload a photo of a cat → get labels like `Cat 🐱, Animal, Pet`.

---

## 🚀 What It Does
An AWS-powered workflow that:
1. Stores uploaded images in **Amazon S3**
2. Sends them to **Amazon Rekognition** for analysis
3. Returns descriptive labels for each image

---

## 🛠 Steps to Run
1. **Create** an S3 bucket for image storage  
2. **Upload** images to the bucket  
3. **Set up** and configure the AWS CLI  
4. **Import** the required Python libraries  
5. **Write** a `detect_labels()` function to call Rekognition  
6. **Add** a `main()` function to run the process  
7. **Execute** the Python script and view the results

---

## ☁️ AWS Services Used
- **Amazon S3** → image storage  
- **Amazon Rekognition** → image analysis & labeling  
- **AWS CLI** → command-line interaction with AWS services  

---

## ➡️ Diagram
This is what the architecture looks like

<img width="1607" height="808" alt="aws_labels_generator_diagram" src="https://github.com/user-attachments/assets/04e5fd7f-a0c4-47cc-8e32-e78294bb9e85" />

---

## ➡️ Final Result
This is what your project will look like, once built:

<img width="796" height="680" alt="aws_labels_generator_final_result" src="https://github.com/user-attachments/assets/8a17b5cf-b494-4c21-bee6-7b321d340786" />
