
# PersonifAI: AI-Driven Personalized Learning Platform



### Revolutionizing Education with AI-Powered Personalization

**PersonifAI** is an AI-driven educational platform designed to provide postgraduate students with personalized learning experiences across core subjects like Data Analytics, Digital Marketing, and Project Management. With features like dynamic quiz generation, real-time adaptive content, and multilingual support, PersonifAI tailors educational content to individual learning paths, fostering inclusivity and accessibility.

---

## 🚀 Project Overview

PersonifAI was developed as part of our capstone project under the mentorship of Dr. Ami Munshi, with a focus on leveraging the latest advancements in AI to support personalized learning. Our goal was to address the limitations of traditional education, such as rigid curricula and lack of adaptability, by creating an intelligent platform that evolves with each learner’s unique needs.

### Key Features

- **Personalized Quizzes and Textbooks**: Generates custom content based on individual progress, ensuring learning material matches each student’s skill level.
- **Multilingual Support**: Powered by Seamless M4T, enabling content in multiple languages (e.g., Hindi, Marathi), making it accessible for non-native English speakers.
- **Dynamic Content Adaptation**: Utilizes Retrieval-Augmented Generation (RAG) to adjust educational resources in real-time.
- **Memory and Speed Optimizations**: Enhanced with LoRA and 4-bit quantization for efficient deployment on consumer-grade GPUs.

## 📑 Project Structure

```plaintext
PersonifAI
│
├── data                  # Dataset and preprocessing scripts
├── models                # Model configurations and training scripts
├── scripts               # Helper scripts for deployment and evaluation
├── notebooks             # Jupyter notebooks for data analysis and experimentation
├── results               # Evaluation metrics and performance logs
└── README.md             # Project documentation
```

## 📦 Setup & Installation

To get started with PersonifAI, follow these steps:

### Prerequisites

- Python 3.8+
- Hugging Face Transformers
- BitsAndBytes, PEFT, TRL
- gTTS (for text-to-speech conversion)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/YourUsername/PersonifAI.git
   cd PersonifAI
   ```

2. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Set up your Hugging Face token and other environment variables.

4. To initiate the model training pipeline, run:

   ```bash
   python scripts/train_model.py
   ```

5. To deploy and access the platform locally, run:

   ```bash
   python app.py
   ```

## 💡 Usage

1. **Model Training**: Run the training script to fine-tune the model on the QA dataset across the three domains.
2. **Dynamic Content Generation**: Use the `generate_content.py` script to create personalized quizzes and textbooks.
3. **Multilingual Support**: Generate audiobooks in various languages using the `text_to_speech.py` script.

## 🧪 Results & Evaluation

- **BERTScore**: Precision 91.21%, Recall 90.66%, F1 90.93%
- **Real-Time Adaptability**: Achieved 92% alignment with learner needs
- **User Feedback**: High engagement with a satisfaction rating of 4.5/5

### Challenges

PersonifAI addresses the high computational demands and scalability issues of LLMs by utilizing 4-bit quantization, making real-time adaptive learning feasible on standard GPUs.

## 🌐 Future Directions

- **Curriculum Expansion**: Extend content to new fields like Finance and Software Engineering.
- **Enhanced Multimodal Learning**: Support video and interactive elements alongside text and audio.
- **Advanced Personalization**: Integrate reinforcement learning for more tailored educational pathways.

## 🤝 Contributors

- **Aum Ghag**
- **Bhavya Bavishi**
- **Nehaal Choudhary**

Special thanks to **Dr. Ami Munshi** for mentorship and guidance.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 💬 Feedback & Support

For questions or feedback, please open an issue in the repository or contact the contributors directly.


