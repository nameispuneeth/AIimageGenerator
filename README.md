# 🧠 AI Image Generator Website

This is a simple web-based application that generates images using AI models hosted on **Hugging Face**. Users can enter a prompt, choose a model, image count, and aspect ratio, then receive AI-generated images in real time.

---


## 🚀 Features

- ✨ Generate multiple AI images based on a custom prompt.
- 📸 Choose different AI models from Hugging Face.
- 📐 Customize image size using aspect ratios.
- 🌓 Toggle between light and dark themes.
- ⚡ Fully responsive and easy to use.

---

## 📁 Project Structure

Project/ <br/>
│<br/>
├── pro2.html # Main HTML file <br/>
├── style2.css # Styling for the UI <br/>
├── ai.js # JavaScript logic for API requests and UI updates <br/>


---

## 🔧 How It Works

1. User enters a prompt and selects options.
2. The app sends multiple API requests to Hugging Face using `fetch()`.
3. The images are returned as blobs and displayed on the page.
4. If an image fails to load, an error message is shown.

---

## 🛠️ Setup Instructions

### 1. Clone or Download the Repository
```bash
git clone https://github.com/your-username/ai-image-generator.git
