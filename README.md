**📘 BudgetWise AI — Your Intelligent Financial Companion**
===========================================================

📸 **Live Application Screenshot**
==================================

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   ![BudgetWise AI Dashboard](https://i.imgur.com/YOUR_SCREENSHOT.png)   `

✨ **Core Features**
===================

### 🔐 **Secure Login & Authentication**

*   SHA256 password hashing
    
*   Local secure SQLite user store
    

### 💸 **Smart Expense & Budget Management**

*   Full CRUD for expenses
    
*   Upload receipts/photos
    
*   Set monthly budgets per category
    

### 🤖 **AI-Powered Finance Tools**

*   **CatBoost ML model** forecasts future expenses
    
*   **Google Gemini Pro** provides personalized financial guidance
    

### 🔁 **Recurring Transactions**

*   Automatic handling of subscriptions, rent, EMIs
    

### 📊 **Interactive Financial Dashboard**

*   Visualizations using **Plotly Express**
    
*   Category-wise spending, monthly trends, predictions
    

### ↔️ **Data Import / Export**

*   Import from CSV
    
*   Export all your expense history
    

### 🎨 **Modern Fluid UI**

*   Clean Streamlit UI
    
*   Dark theme optimized for long sessions
    

🏗️ **Tech Stack Overview**
===========================

LayerTechnology**Frontend**Streamlit**Backend**Python 3**Database**SQLite**AI Model**CatBoost Regressor**Generative AI**Google Gemini Pro**Visualization**Plotly Express**Data Processing**Pandas, NumPy

⚙️ **Installation Guide**
=========================

**1\. Clone the Repository**
----------------------------

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   git clone https://github.com/your-username/BudgetWise-AI.git  cd BudgetWise-AI   `

**2\. Create & Activate Virtual Environment**
---------------------------------------------

**Windows**

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   python -m venv .venv  .venv\Scripts\activate   `

**Mac / Linux**

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   python3 -m venv .venv  source .venv/bin/activate   `

**3\. Install Dependencies**
----------------------------

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   pip install -r requirements.txt   `

**4\. Add Your Gemini API Key**
-------------------------------

Create .streamlit/secrets.toml:

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   GEMINI_API_KEY = "YOUR_API_KEY_HERE"   `

_Already included in .gitignore for safety._

**5\. Run the App**
-------------------

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   streamlit run app.py   `

📂 **Project Structure**
========================

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   BudgetWise-AI/  ├── .streamlit/  │   └── secrets.toml  ├── models/  │   └── best_finance_model.pkl  ├── app.py  ├── .gitignore  ├── README.md  └── requirements.txt   `

🚀 **Roadmap (Upcoming Features)**
==================================

*   Multi-user cloud database (Firebase/PostgreSQL)
    
*   SMS/email bill reminders
    
*   Auto-categorization using AI
    
*   Expense anomaly detection
    
*   Mobile-friendly layout
    

🤝 **Contributing**
===================

Pull requests are welcome!Steps:

1.  Fork the repo
    
2.  Create a branch
    
3.  Commit changes
    
4.  Submit a PR


TEAM
Edupulapati Sai Praneeth
    

📝 **License**
==============

This project is licensed under the **MIT License**.See the [LICENSE](https://chatgpt.com/c/LICENSE) file for details.
Made by E Sai Praneeth
