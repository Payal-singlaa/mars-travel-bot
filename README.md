# Mars Travel Chatbot with Amazon Lex & Bedrock

## 🚀 Overview
This project is a **Mars Travel Chatbot** built using **Amazon Lex, Amazon Bedrock, and AWS CloudFormation**. It allows users to interact with a chatbot that leverages **Retrieval Augmented Generation (RAG)** to provide intelligent responses based on stored travel policy documents. The chatbot is integrated with a **custom web UI** deployed using **AWS CloudFormation**.

## 🛠 Features
- **Conversational AI Chatbot**: Built with **Amazon Lex** and powered by **Amazon Bedrock** for generative AI capabilities.
- **Retrieval Augmented Generation (RAG)**: Uses **Amazon Bedrock Knowledge Base** to fetch relevant information from stored documents.
- **Document Storage & Management**: Utilizes **Amazon S3** to store travel policy documents.
- **Web-Based UI**: A user-friendly chatbot interface deployed using **AWS CloudFormation**.
- **Multi-Model Support**: Implements **Amazon Titan Embeddings** and **Anthropic Claude v2** for natural language understanding and response generation.

## 🏗 Architecture
1. **Amazon S3**: Stores travel policy documents.
2. **Amazon Bedrock**: Provides generative AI capabilities with **Titan Embeddings & Claude v2**.
3. **Amazon Bedrock Knowledge Base**: Connects to S3 to retrieve and process relevant data.
4. **Amazon Lex**: Serves as the conversational AI interface.
5. **AWS CloudFormation**: Deploys the web UI for the chatbot.
6. **Custom Web UI**: An intuitive frontend for users to interact with the chatbot.

## 🔧 Tools & Technologies
- **Amazon Lex** – Conversational AI chatbot
- **Amazon Bedrock** – AI-powered knowledge base & retrieval system
- **Amazon S3** – Document storage
- **Amazon Titan Embeddings & Anthropic Claude v2** – AI models for language processing
- **AWS CloudFormation** – Infrastructure as Code (IaC) for deploying the web UI
- **Web UI** – A custom interface for chatbot interaction

## 📌 Setup Instructions
### Prerequisites
- An **AWS account** with access to:
  - **Amazon Bedrock** (Titan Embeddings G1 & Claude v2)
  - **Amazon Lex**
  - **Amazon S3**
  - **AWS CloudFormation**

### Deployment Steps
1. **Set Up Amazon Bedrock Models**
   - Request access to **Titan Embeddings G1 – Text** and **Anthropic Claude v2**.
2. **Create an S3 Bucket**
   - Upload travel policy documents to serve as the chatbot’s knowledge base.
3. **Set Up Amazon Bedrock Knowledge Base**
   - Link it to the S3 bucket to enable retrieval-augmented responses.
4. **Create Amazon Lex Chatbot**
   - Configure intents, slots, and responses.
5. **Deploy Web UI using AWS CloudFormation**
   - Use a CloudFormation template to set up the chatbot’s frontend.

## 📈 Future Enhancements
- **Multi-language support** for a global user base.
- **Voice interaction support** for hands-free chatbot usage.
- **Integration with additional AI models** for improved accuracy.
- **Enhanced UI design** for a better user experience.
- **Logging & analytics** to monitor chatbot performance.

## 📜 License
This project is open-source. Feel free to use and modify it for your needs.

---
### 🚀 Connect & Contribute
Found this project useful? Feel free to **star** ⭐ the repo and contribute by submitting **pull requests** or **reporting issues**! 🎉

