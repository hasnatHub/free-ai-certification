# AI Certificate Explorer

🚀 **Your Gateway to Free AI Expertise**

## Description
The AI Certificate Explorer is a single-page, interactive web application designed to help users discover free online certifications, courses, and digital badges in Artificial Intelligence (AI), Machine Learning (ML), Data Science, Deep Learning, Generative AI, and LLM Security. This community-driven resource empowers learners to enhance their AI skills and earn verifiable credentials without financial barriers.

## Table of Contents
- [Features](#features)
- [Live Demo](#live-demo)
- [Certifications List](#certifications-list)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Interactive Dashboard**: Visualize the AI learning landscape with dynamic charts showing credential types and top providers.
- **Filterable Certifications**: Find courses by AI domain (e.g., Generative AI, Deep Learning) or credential type (e.g., Digital Badge, Completion Certificate).
- **Detailed Course Information**: View key topics, duration, and direct course links via certification card modals.
- **Learning Journey Guide**: Actionable advice on strategic learning, portfolio building, and leveraging credentials.
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices.

## Live Demo
Explore the live demo hosted on GitHub Pages:  
[AI Certificate Explorer](https://balavenkatesh3322.github.io/free-ai-certification/)

## Certifications List
A comprehensive list of free AI, ML, Data Science, and related certifications included in the explorer:

| **Domain** | **Provider** | **Course/Certification Name** | **Free Credential?** | **Key Topics** | **Duration** | **Link** |
|------------|--------------|-------------------------------|----------------------|----------------|--------------|----------|
| AI/ML/Data Science | Google Cloud | Build and Deploy Machine Learning Solutions on Vertex AI | Yes (Digital Badge) | Vertex AI, AutoML, Custom Training, Model Deployment | 7 hours | [Link](#) |
| AI/ML/Data Science | IBM | Artificial Intelligence Fundamentals | Yes (Digital Badge) | AI concepts, ML, Deep Learning, Chatbots, AI Ethics | 10 hours | [Link](#) |
| AI/ML/Data Science | IBM | Data Fundamentals | Yes (Digital Badge) | Data analytics, methodologies, tools, Python | 7 hours | [Link](#) |
| AI/ML/Data Science | IBM | AI for Everyone: Master the Basics | Yes (Digital Badge) | AI applications, ML, Deep Learning, Neural Networks, Gen AI | 4 weeks (1-2 hrs/week) | [Link](#) |
| Deep Learning | Great Learning | Introduction to Deep Learning | Yes (Completion Certificate) | Deep Learning, Neural Networks, CNN, RNN, Python | 3.5 hours | [Link](#) |
| Generative AI & LLMs | IBM | Generative AI: Introduction and Applications | Yes (Digital Badge) | Generative AI, ChatGPT, Prompt Engineering, LLMs | 1-4 weeks | [Link](#) |
| Generative AI & LLMs | IBM | Generative AI in Action | Yes (Digital Badge) | Gen AI principles, Prompt Engineering, Python libraries | 5+ hours | [Link](#) |
| Generative AI & LLMs | Salesforce | Salesforce Certified Agentforce Specialist | Yes (Free Exam until March 2025) | Agentforce, Prompt Engineering, RAG, Fine-tuning | Exam | [Link](#) |
| Generative AI & LLMs | Google Cloud | Introduction to Generative AI | No (Audit Only) | Generative AI, Application Development, AI, ML Methods | 1-4 weeks | [Link](#) |
| Generative AI & LLMs | DeepLearning.AI | ChatGPT Prompt Engineering for Developers | No (Completion Email Only) | Prompt Engineering, LLMs for summarizing, inferring | 1.5 hours | [Link](#) |
| Generative AI & LLMs | Cohere | LLM University | No (Not mentioned) | LLM basics, architecture, fine-tuning, applications | Self-paced | [Link](#) |
| Generative AI & LLMs | Hugging Face | NLP Course | No (Not mentioned) | NLP basics, LLMs, Transformers, text generation | Self-paced | [Link](#) |
| LLM Security & AI Governance | Securiti Education | AI Security & Governance Certification | Yes (Completion Certificate) | Gen AI risks, Global AI laws, LLM firewalls | 2-2.5 hours | [Link](#) |
| Other AI-related | OpenCV University | Free OpenCV Course | Yes (Official Certification) | Image/Video manipulation, Object/Face detection | 3 hours | [Link](#) |
| Other AI-related | Great Learning | Reinforcement Learning with Python | Yes (Completion Certificate) | RL introduction, Q-learning, Python implementation | 8.25 hours | [Link](#) |
| Other AI-related | Great Learning | Introduction to Natural Language Processing | Yes (Completion Certificate) | NLP basics, Text Mining, Chatbots, Sentiment Analysis | 4.5 hours | [Link](#) |

**Note**: Replace placeholder `[Link](#)` with actual course URLs.

## Roadmap
Future enhancements to make AI Certificate Explorer the go-to resource for free AI education:
- **Expanded Data**: Add more free certifications and courses.
- **Provider Filtering**: Filter courses by specific providers.
- **Search Functionality**: Add a search bar for keyword-based course discovery.
- **User Accounts**: Optional accounts to save favorites and track progress.
- **"New" Badges**: Highlight newly added certifications.
- **Community Contributions**: Enable users to suggest courses via a UI form.
- **Advanced Analytics**: Provide insights into popular domains and trends.

## Contributing
We welcome contributions to keep this resource comprehensive and user-friendly! To contribute:

1. **Fork the Repository**: Fork [free-ai-certification](https://github.com/balavenkatesh3322/free-ai-certification).
2. **Clone Your Fork**:
   ```bash
   git clone https://github.com/your-username/free-ai-certification.git
   cd free-ai-certification
   ```
3. **Create a Branch**:
   ```bash
   git checkout -b feature/your-feature-name
   ```
4. **Make Changes**:
   - **Add Certifications**: Update the `certData` array in `index.html` with new course details, ensuring accurate `isTrulyFree` and `credentialType` fields.
   - **Improve UI/UX**: Modify HTML and Tailwind CSS.
   - **Fix Bugs**: Address JavaScript or HTML issues.
5. **Test Changes**: Open `index.html` in a browser to verify functionality.
6. **Commit Changes**:
   ```bash
   git add .
   git commit -m "feat: Add new certification"
   ```
7. **Push to Your Fork**:
   ```bash
   git push origin feature/your-feature-name
   ```
8. **Create a Pull Request**: Submit a PR on GitHub with a clear title and description.

### Code Style
- **HTML**: Use semantic structure.
- **CSS**: Use Tailwind CSS; avoid custom CSS unless necessary.
- **JavaScript**: Write clean, readable vanilla JavaScript with consistent naming.
- **Data**: Adhere to the `certData` object structure.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
