# 📚 AI MCQ Generator from Book Images

A web-based application that generates Multiple Choice Questions (MCQs) from book images using OCR technology.

## ✨ Features

- 📸 Upload images of book pages
- 🔍 Automatic text extraction using OCR (Tesseract.js)
- 🎯 Generate random MCQs with three difficulty levels:
  - Easy (3 options)
  - Medium (4 options)
  - Hard (4 options)
  - Mixed (random difficulty)
- 📊 Choose how many questions to generate (1-20)
- ✅ Automatic answer checking
- 📈 Score tracking and results display
- 🎨 Beautiful, responsive design

## 🚀 How to Host on GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right and select "New repository"
3. Name your repository (e.g., `mcq-generator`)
4. Make sure it's set to **Public**
5. Click "Create repository"

### Step 2: Upload the File

1. In your new repository, click "Add file" → "Upload files"
2. Drag and drop the `index.html` file or click to select it
3. Scroll down and click "Commit changes"

### Step 3: Enable GitHub Pages

1. In your repository, click "Settings" (top menu)
2. Scroll down to "Pages" in the left sidebar
3. Under "Source", select "main" branch
4. Click "Save"
5. Wait a few minutes for deployment

### Step 4: Access Your Site

Your site will be available at:
```
https://YOUR-USERNAME.github.io/REPOSITORY-NAME/
```

For example: `https://johnsmith.github.io/mcq-generator/`

## 📖 How to Use

1. **Upload Image**: Click "Upload Book Image" and select an image of book text
2. **Configure Settings**:
   - Choose difficulty level (Easy/Medium/Hard/Mixed)
   - Select number of questions (1-20)
3. **Generate**: Click "Generate MCQs" button
4. **Answer Questions**: Click on your chosen answer for each question
5. **Submit**: Click "Submit Answers" to see your score
6. **Review**: See correct/incorrect answers highlighted in green/red

## 🎯 Tips for Best Results

- **Image Quality**: Use clear, high-resolution images with good lighting
- **Text Clarity**: Ensure text is readable and not blurry
- **Language**: Currently supports English text only
- **Text Amount**: More text in the image allows for more questions to be generated
- **File Format**: Supports JPG, PNG, and other common image formats

## 🔧 Technical Details

- **OCR Engine**: Tesseract.js (loaded from CDN)
- **No Backend Required**: Everything runs in the browser
- **Privacy**: Images are processed locally, not uploaded to any server
- **Mobile Friendly**: Responsive design works on all devices

## 📝 How It Works

1. **Text Extraction**: Uses Tesseract.js OCR to extract text from uploaded images
2. **Question Generation**: Analyzes extracted text and creates fill-in-the-blank questions
3. **Answer Options**: Generates plausible wrong answers based on context
4. **Difficulty Scaling**: Adjusts number of options based on difficulty level
5. **Scoring**: Tracks user answers and calculates final score

## ⚙️ Customization

You can customize the application by editing the `index.html` file:

- **Colors**: Change the gradient colors in the CSS section
- **Max Questions**: Modify the `max="20"` attribute in the number input
- **Difficulty Options**: Add/remove difficulty levels in the select element
- **Styling**: Update CSS styles to match your preferences

## 🐛 Troubleshooting

**No questions generated?**
- Ensure the image contains clear, readable text
- Try uploading a higher quality image
- Reduce the number of questions requested

**OCR not working?**
- Check your internet connection (Tesseract.js loads from CDN)
- Try a different browser
- Ensure the image format is supported

**Questions seem random/incorrect?**
- This is expected - the app generates questions automatically
- For better results, use images with more contextual text
- Consider this a study aid rather than a perfect quiz generator

## 📄 License

Free to use and modify for personal and educational purposes.

## 🤝 Contributing

Feel free to fork and improve this project! Some ideas:
- Add support for multiple languages
- Improve question generation algorithm
- Add export functionality for questions
- Create a question bank feature
- Add timer functionality

## 📧 Support

If you encounter issues, please check that:
- Your image is clear and readable
- You have a stable internet connection
- You're using a modern web browser (Chrome, Firefox, Safari, Edge)

---

**Enjoy creating MCQs from your book images! 📚✨**
