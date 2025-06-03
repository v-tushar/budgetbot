# FinGenius: AI Personal Finance Advisor

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![Jupyter](https://img.shields.io/badge/jupyter-notebook-orange.svg)

## 🚀 Project Overview

FinGenius is an AI-powered personal finance advisor that helps users analyze their spending patterns, provides personalized financial recommendations, and answers finance-related questions with reliable sources. This project was developed as part of the **Kaggle 5-Day Gen AI Intensive Course Capstone Project**, showcasing multiple Gen AI capabilities in a practical financial advisory application.

## 🎯 Problem Statement

Many individuals struggle with managing their finances effectively. They need help with:
- Understanding their spending patterns
- Getting personalized financial advice
- Learning about financial concepts and best practices
- Creating and maintaining budgets
- Planning for financial goals

FinGenius addresses these needs by providing an intelligent assistant that can analyze transaction data, offer personalized recommendations, and answer finance-related questions in a conversational manner.

## 🤖 Gen AI Capabilities Demonstrated

This project showcases **5 key Gen AI capabilities**:

### 1. 📊 Structured Output/JSON Mode
- Transaction categorization and analysis
- Budget breakdown visualization
- Financial health summary reports
- Expense pattern detection

### 2. 🔍 RAG (Retrieval Augmented Generation)
- Financial knowledge base for answering questions
- Retrieval of financial best practices and advice
- Access to financial regulations and terminology
- Personalized recommendations based on financial literature

### 3. 🧠 Embeddings
- Semantic understanding of transaction descriptions
- Clustering similar expenses
- Finding spending patterns over time
- Similarity search for financial concepts

### 4. 🛠️ Function Calling
- Financial calculations (savings projections, interest calculations)
- Data processing and transformation
- External API integration for financial data
- Budget allocation algorithms

### 5. 🤖 Agents with LangGraph
- Conversational financial advisor workflow
- Multi-step financial planning process
- Decision trees for financial recommendations
- State management for ongoing financial conversations

## 📁 Project Structure

```
fin_genius-ai-agent/
├── FinGenius_Kaggle_Notebook.ipynb          # Main implementation notebook
├── fingenius-notebook-gemini-agent.ipynb    # Agent-focused implementation
├── fingenius_notebook_updated.ipynb         # Updated version with improvements
├── fingenius_notebook.ipynb                 # Original notebook
├── install_dependencies.py                  # Dependency installation script
├── project_structure.md                     # Detailed project documentation
├── todo.md                                  # Development checklist
├── LICENSE                                  # MIT License
└── README.md                                # This file
```

## 🛠️ Installation & Setup

### Prerequisites
- Python 3.8 or higher
- Jupyter Notebook or JupyterLab
- Google API Key (for Gemini AI)

### Quick Start

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/fin_genius-ai-agent.git
   cd fin_genius-ai-agent
   ```

2. **Install dependencies:**
   ```bash
   python install_dependencies.py
   ```

3. **Set up your Google API Key:**
   - Get your API key from [Google AI Studio](https://makersuite.google.com/)
   - Set it up in your environment (the notebooks use secure methods to access the key)

4. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

5. **Open and run the main notebook:**
   - Start with `FinGenius_Kaggle_Notebook.ipynb` for the complete implementation

## 💡 Key Features

- **🔍 Smart Transaction Analysis**: Automatically categorizes and analyzes your financial transactions
- **💬 Conversational Interface**: Natural language interaction for financial queries
- **📈 Spending Insights**: Identifies patterns and trends in your financial behavior
- **🎯 Personalized Recommendations**: Tailored advice based on your financial profile
- **📚 Financial Knowledge Base**: Access to comprehensive financial information and best practices
- **🤖 Multi-Agent System**: Sophisticated workflow for complex financial planning scenarios

## 🎮 Usage Examples

The notebooks contain comprehensive examples of:
- Loading and analyzing transaction data
- Generating financial insights and recommendations
- Conversational interactions with the AI advisor
- Visualizing spending patterns and financial health
- Planning budgets and financial goals

## 🧪 Notebooks Overview

| Notebook | Description |
|----------|-------------|
| `FinGenius_Kaggle_Notebook.ipynb` | **Main implementation** - Complete showcase of all 5 Gen AI capabilities |
| `fingenius-notebook-gemini-agent.ipynb` | **Agent-focused** - Deep dive into LangGraph agent implementation |
| `fingenius_notebook_updated.ipynb` | **Enhanced version** - Improved features and optimizations |
| `fingenius_notebook.ipynb` | **Original version** - Initial implementation and experiments |

## 🔒 Security & Privacy

- API keys are handled securely using environment variables
- No sensitive financial data is hardcoded
- All examples use synthetic/sample data
- Follows best practices for handling personal financial information

## 🚧 Limitations & Future Improvements

- Currently uses sample/synthetic data for demonstrations
- Real-time financial data integration could be enhanced
- Additional visualization capabilities could be added
- More sophisticated risk assessment algorithms
- Mobile app interface development

## 🤝 Contributing

This project was developed as a capstone project, but contributions and improvements are welcome! Please feel free to:
- Fork the repository
- Create feature branches
- Submit pull requests
- Report issues or suggest enhancements

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Kaggle 5-Day Gen AI Intensive Course** for the learning opportunity
- **Google Gemini AI** for powering the AI capabilities
- **LangChain/LangGraph** community for the agent framework
- Open-source community for the various libraries used

## 📞 Contact & Support

For questions, suggestions, or collaboration opportunities, please open an issue in this repository.

---

**⭐ If you find this project helpful, please consider starring the repository!** 