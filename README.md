# AI-Powered Image Captioning Chatbot for University Website

This project is a Flask-based web application that integrates an **AI-powered image captioning model**. The application allows users to upload an image, and the AI generates a descriptive caption for it. It utilizes the **ViT-GPT2 model** from Hugging Face's Transformers library, combining a Vision Transformer (ViT) for image processing with GPT-2 for language generation.

---

## 🚀 **Features**
- **Image Captioning**: Automatically generates captions for uploaded images.
- **State-of-the-Art Model**: Powered by the `nlpconnect/vit-gpt2-image-captioning` model.
- **Web-Based Interface**: Simple and interactive interface built with Flask.
- **Device Compatibility**: Supports both GPU (CUDA) and CPU for processing.

---

## 🛠️ **Technologies Used**
1. **Programming Language**: Python
2. **Framework**: Flask
3. **Libraries**:
   - Transformers: For the ViT-GPT2 model.
   - PIL (Pillow): For image processing.
   - Torch: For deep learning computations.
   - Flask: For creating the web application.

---

## 📋 **Setup Instructions**

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/image-captioning-chatbot.git
cd image-captioning-chatbot
```

### 2. Install Dependencies
Make sure Python 3.7+ is installed. Then, install the required libraries:
```bash
pip install flask torch transformers pillow matplotlib
```

### 3. Download the Model
The code automatically downloads the `nlpconnect/vit-gpt2-image-captioning` model and tokenizer when you run the application for the first time.

### 4. Prepare the HTML Template
Place your `index.html` file in the appropriate directory. For example:
```plaintext
project-directory/
│
├── app.py
├── templates/
│   └── index.html
```

### 5. Run the Application
Start the Flask server:
```bash
python app.py
```

The application will be accessible at `http://127.0.0.1:5000`.

---

## 📂 **Project Files**
- `app.py`: Main Flask application.
- `index.html`: HTML template for the web interface.
- Additional model and tokenizer files: Automatically downloaded when the app runs.

---

## 🎯 **How It Works**
1. **User Interaction**: Users upload an image through the web interface.
2. **Image Processing**: The uploaded image is processed by the Vision Transformer (ViT) feature extractor.
3. **Caption Generation**: The processed image is passed to the GPT-2 model, which generates a descriptive caption.
4. **Response**: The generated caption is displayed on the webpage or returned as JSON.

---

## 🎨 **Customization**
- **Modify Captions**: Adjust parameters like `max_length` and `num_beams` in the `gen_kwargs` dictionary to control caption generation.
- **Enhance the Interface**: Customize `index.html` for a better user experience.
- **Extend Functionality**: Integrate the captioning feature with additional AI-based features like object detection or text-to-speech.

---

## 📊 **Potential Applications**
- University website enhancements for accessibility (e.g., automatic alt-text generation for images).
- Integration into content management systems for automatic image descriptions.
- AI-driven tools for education and student engagement.

---

## 🤝 **Contributions**
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m "Add feature"`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

---

## 📜 **License**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 📧 **Contact**
For questions or suggestions, reach out:
- **Email**: Addyabir111@gmail.com
- **GitHub**: [AbirDas-5151](https://github.com/AbirDas-5151)

---

## 📝 **Acknowledgments**
- **Hugging Face Transformers**: For the ViT-GPT2 model.
- **Flask**: For enabling rapid web application development.
- **Pillow**: For seamless image processing.

Let’s make AI more accessible and impactful! 😊
