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
