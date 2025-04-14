# ⚡ Generative AI Project using AWS Bedrock & S3 (via Console UI)

This project walks through how to build a Generative AI workflow using **AWS Bedrock** and **Amazon S3**, all through the **AWS Console UI** — no code needed for setup! You can use this as a foundation for AI content generation, file-based automation, or scalable cloud-backed AI applications.

---

## 📚 Table of Contents

- [Project Overview](#-project-overview)
- [Steps (UI-Based)](#-steps-ui-based)
  - [1. Create an S3 Bucket](#1-create-an-s3-bucket)
  - [2. Upload Your Input File](#2-upload-your-input-file)
  - [3. Open AWS Bedrock Console](#3-open-aws-bedrock-console)
  - [4. Choose a Foundation Model](#4-choose-a-foundation-model)
  - [5. Provide Prompt and Generate](#5-provide-prompt-and-generate)
  - [6. Copy Output and Store in S3](#6-copy-output-and-store-in-s3)
- [Future Plans](#-future-plans)
- [License](#-license)

---

## 🔍 Project Overview

This project:
- Uses **Amazon S3** for uploading and storing input data.
- Leverages **AWS Bedrock’s foundation models** (like Claude, Titan, etc.) to generate AI responses.
- Requires **no code** to get started.
- Can be expanded into a full-stack GenAI app later.

---

## 🪜 Steps (UI-Based)

### 1. Create an S3 Bucket

> Head over to the **S3** section in the AWS Console.

![image](https://github.com/user-attachments/assets/2b1b461a-8224-44bf-a116-5e30e97fd86e)

- Give your bucket a unique name: `genai-database-demo`
- Leave the region default or choose nearest to you.
- Uncheck "Block all public access" **only** if required (not recommended).

---

### 2. Upload Input Files to S3

📷 _Screenshot of uploading `prompt.txt` or similar_

- Go into the bucket → Click **Upload**
- Upload your prompt file(s), e.g., `prompt1.txt`, `summary_request.txt`

---

### 3. Open AWS Bedrock Console

![image](https://github.com/user-attachments/assets/7db78a9d-3ccd-4993-a4df-38297da27662)
![image](https://github.com/user-attachments/assets/17aecd79-8af8-4cc5-a163-38918be48c6d)
![image](https://github.com/user-attachments/assets/49966ddd-9413-4487-9460-d4eeea0713db)
![image](https://github.com/user-attachments/assets/fd541295-8a7c-4109-8f8d-0ffdeb2b2248)
![image](https://github.com/user-attachments/assets/96de9c24-2247-4cdd-89fa-ec766790343e)


- Search **Bedrock** in AWS Console and click it
- Navigate to **Playground** section

---

### 4. Choose a Foundation Model

![image](https://github.com/user-attachments/assets/a0310e24-6271-4b7c-9b0e-d217bfda9a7d)
![image](https://github.com/user-attachments/assets/c998c203-316c-4d78-9c2c-ba39e8667e26)

- Select your desired model (e.g., **Claude v2**, **Titan Text**)
- Click **“Text” playground** to begin generating

---

### 5. Provide Prompt and Generate

![image](https://github.com/user-attachments/assets/a3d5b70e-72a2-45c8-b509-1339334c4ab0)

- Paste or write your prompt
- Adjust temperature or max tokens if needed
- Click **“Generate”** to view model response

---


## 🧠 References

- [Amazon Bedrock Documentation](https://docs.aws.amazon.com/bedrock/)
- [Amazon S3 Documentation](https://docs.aws.amazon.com/s3/)
