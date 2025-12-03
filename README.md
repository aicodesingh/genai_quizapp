# 🧠 AWS AI Practitioner (AIF-C01) Interactive Study Guide

<div align="center">

![AWS AI Practitioner](https://img.shields.io/badge/AWS-AI%20Practitioner-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**A comprehensive, self-contained quiz and flashcard application for mastering AWS Generative AI concepts**

[Live Demo](#-quick-start) • [Features](#-features) • [Topics Covered](#-topics-covered) • [Contributing](#-contributing)

</div>

---

## 📖 Overview

This interactive study guide is designed to help you prepare for the **AWS Certified AI Practitioner (AIF-C01)** exam. It features randomized multiple-choice questions with instant feedback and a comprehensive flashcard system—all in a single, dependency-free HTML file that runs entirely in your browser.

<div align="center">
<img src="https://img.shields.io/badge/Questions-35+-4ecdc4?style=flat-square" alt="35+ Questions"/>
<img src="https://img.shields.io/badge/Flashcards-45+-ff6b35?style=flat-square" alt="45+ Flashcards"/>
<img src="https://img.shields.io/badge/Dependencies-Zero-10b981?style=flat-square" alt="Zero Dependencies"/>
<img src="https://img.shields.io/badge/Offline-Ready-a78bfa?style=flat-square" alt="Offline Ready"/>
</div>

---

## ✨ Features

### 🎯 Quiz Mode
- **35+ carefully crafted MCQs** covering core exam topics
- **Randomized questions & answers** on each session to prevent pattern memorization
- **Instant feedback** with detailed explanations for both correct and incorrect answers
- **Progress tracking** with real-time score updates
- **Category tags** for each question to identify knowledge gaps
- **Results summary** with performance breakdown

### 🃏 Flashcard Mode
- **45+ concept cards** for rapid review
- **Click-to-flip** interaction with smooth 3D animations
- **Shuffle functionality** for varied practice sessions
- **Keyboard navigation** support for efficient studying

### 🎨 Design & UX
- **Modern dark theme** optimized for extended study sessions
- **Fully responsive** layout for desktop, tablet, and mobile
- **Zero dependencies** — runs entirely offline
- **Single HTML file** — easy to download, share, and host

---

## 📚 Topics Covered

| Category | Description |
|----------|-------------|
| **Amazon SageMaker** | Ground Truth Plus, Canvas, JumpStart, Studio security |
| **Amazon Bedrock** | Foundation models, cross-region inference, Jamba model |
| **VPC Security** | Network isolation, PrivateLink, endpoint policies, security groups |
| **IAM & Access Control** | Presigned URLs, source IP conditions, VPC endpoint conditions |
| **ML Fundamentals** | Regularization (L1/L2), dropout, overfitting prevention |
| **Human-in-the-Loop** | Amazon A2I, Ground Truth Plus workflows |
| **RAG Architecture** | LangChain, LangGraph, Bedrock integration patterns |
| **Security Frameworks** | Generative AI Security Scoping Matrix |
| **Transfer Learning** | Layer preservation, classifier fine-tuning |
| **Observability** | AgentCore Observability for Bedrock debugging |

---

## 🚀 Quick Start

### Option 1: Direct Download
1. Download `aws_aip_c01_quiz.html`
2. Open in any modern web browser
3. Start studying!

### Option 2: Clone Repository
```bash
git clone https://github.com/yourusername/aws-ai-practitioner-quiz.git
cd aws-ai-practitioner-quiz
open aws_aip_c01_quiz.html  # macOS
# or
start aws_aip_c01_quiz.html  # Windows
# or
xdg-open aws_aip_c01_quiz.html  # Linux
```

### Option 3: GitHub Pages
Visit the live demo at: `https://yourusername.github.io/aws-ai-practitioner-quiz/`

---

## ⌨️ Keyboard Shortcuts

| Key | Quiz Mode | Flashcard Mode |
|-----|-----------|----------------|
| `←` | Previous question | Previous card |
| `→` | Next question | Next card |
| `Space` | — | Flip card |
| `Enter` | — | Flip card |

---

## 🖥️ Browser Support

| Browser | Supported |
|---------|-----------|
| Chrome | ✅ |
| Firefox | ✅ |
| Safari | ✅ |
| Edge | ✅ |
| Opera | ✅ |

---

## 📁 Project Structure

```
aws-ai-practitioner-quiz/
├── aws_aip_c01_quiz.html    # Self-contained quiz application
├── README.md                 # This file
└── LICENSE                   # MIT License
```

---

## 🛠️ Technical Details

- **Pure vanilla JavaScript** — no frameworks or libraries required
- **Embedded CSS** with CSS custom properties for easy theming
- **LocalStorage-free** — no tracking, fully private
- **Fisher-Yates shuffle** algorithm for true randomization
- **Responsive breakpoints** at 768px for mobile optimization

---

## 📈 Study Tips

1. **First Pass**: Go through all flashcards to familiarize yourself with concepts
2. **Quiz Mode**: Take the full quiz and note your weak areas (check category tags)
3. **Targeted Review**: Use flashcards to reinforce topics where you scored lower
4. **Repeat**: The randomization ensures each session feels fresh
5. **Track Progress**: Aim for consistent 80%+ scores before the exam

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/new-questions`)
3. **Add** new questions or flashcards following the existing format
4. **Commit** your changes (`git commit -m 'Add questions on Amazon Q'`)
5. **Push** to the branch (`git push origin feature/new-questions`)
6. **Open** a Pull Request

### Adding New Questions

Questions follow this structure:
```javascript
{
    question: "Your question text here?",
    options: [
        { text: "Option A text", correct: false },
        { text: "Option B text", correct: true },
        { text: "Option C text", correct: false },
        { text: "Option D text", correct: false }
    ],
    explanation: "Detailed explanation of why the correct answer is right.",
    category: "Category Name"
}
```

---

## 📜 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

## ⚠️ Disclaimer

This study guide is an **unofficial** resource created for educational purposes. It is not affiliated with, endorsed by, or sponsored by Amazon Web Services (AWS). AWS, Amazon SageMaker, Amazon Bedrock, and other AWS service names are trademarks of Amazon.com, Inc.

Always refer to the [official AWS documentation](https://aws.amazon.com/certification/certified-ai-practitioner/) and exam guides for the most current and accurate information.

---

## 🙏 Acknowledgments

- AWS Documentation for reference material
- The AWS community for exam insights and study tips

---

<div align="center">

**Good luck with your certification! 🎓**

Made with ☕ and determination

[![GitHub stars](https://img.shields.io/github/stars/yourusername/aws-ai-practitioner-quiz?style=social)](https://github.com/yourusername/aws-ai-practitioner-quiz)

</div># genai_quizapp
