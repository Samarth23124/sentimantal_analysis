# Sentiment Analysis and Mental Health Support System

## Project Overview
This project implements a sophisticated sentiment analysis and mental health support system that combines multiple AI technologies to provide personalized assistance. The system uses sentiment analysis to understand user emotions and provides context-aware responses through a conversational interface.

## Key Features
1. **Sentiment Analysis**: Real-time emotion detection using Hugging Face's transformers
2. **AI-Powered Chat Interface**: Interactive chat system with a psychologist persona
3. **Knowledge Integration**: 
   - Wikipedia integration for factual information
   - Mental health resources from Medical News Today
   - Vector-based knowledge retrieval system
4. **Advanced AI Models**:
   - Groq's LLaMA 3.3 70B model for intelligent responses
   - FAISS for efficient vector similarity search
   - Hugging Face embeddings for semantic understanding

## Technical Architecture

### Core Components
1. **Frontend**: Streamlit-based web interface
2. **Backend Services**:
   - Sentiment Analysis Pipeline
   - Knowledge Retrieval System
   - AI Chat Agent
3. **Data Processing**:
   - Document loading and splitting
   - Vector embeddings
   - Semantic search capabilities

### Dependencies
The project uses several key Python packages:
- Transformers (Hugging Face)
- LangChain and its ecosystem
- Streamlit
- FAISS
- Various AI model integrations

## Setup Instructions

### Prerequisites
- Python 3.8 or higher
- GROQ API key
- Required Python packages (listed in requirements.txt)

### Installation
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Create a `.env` file with your GROQ API key:
   ```
   GROQ_API_KEY=your_api_key_here
   ```

### Running the Application
1. Start the Streamlit application:
   ```bash
   streamlit run app.py
   ```
2. Access the application through your web browser

## Project Phases

### Phase 1: Foundation Setup
- [x] Project initialization
- [x] Basic dependency setup
- [x] Environment configuration

### Phase 2: Core Implementation
- [x] Sentiment analysis integration
- [x] Streamlit interface development
- [x] Basic chat functionality

### Phase 3: Advanced Features
- [x] Knowledge base integration
- [x] Vector database implementation
- [x] AI agent development

### Phase 4: Integration and Testing
- [x] Component integration
- [x] System testing
- [x] Performance optimization

## Usage Guide

### Sentiment Analysis
1. Enter your feelings in the sidebar text input
2. The system will analyze and display the sentiment

### Chat Interface
1. Type your message in the chat input
2. The AI psychologist will respond based on:
   - Your current sentiment
   - Available knowledge base
   - Contextual understanding

## Future Enhancements
1. Enhanced knowledge base integration
2. Multi-language support
3. Advanced analytics dashboard
4. Integration with additional mental health resources

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Hugging Face for the sentiment analysis model
- Groq for the LLaMA model access
- Medical News Today for mental health resources
- Wikipedia for factual information 