# Hackathon-MedGaurd-Multi-Agent-System
MedGuard AI is an intelligent, multi-agent sepsis detection and management system that combines artificial intelligence with human clinical expertise to provide real-time, evidence-based support for early sepsis identification and treatment.

# MedGuard AI - Multi-Agent Sepsis Detection System

## 🎯 Overview

MedGuard AI is an intelligent, multi-agent sepsis detection and management system that combines artificial intelligence with human clinical expertise to provide real-time, evidence-based support for early sepsis identification and treatment.

## 🚀 Features

- **Multi-Agent AI System**: 4 specialized agents for comprehensive analysis
- **Real-time Analysis**: Continuous patient monitoring and risk assessment
- **Human-in-the-Loop**: Clinical decision support with human oversight
- **Comprehensive Dataset**: 13 diverse patient cases for testing and education
- **Modern Web Interface**: Responsive design with Bootstrap 5
- **Azure OpenAI Integration**: Powered by GPT-5 for advanced clinical reasoning

## 🤖 AI Agents

1. **Monitor Agent 🔍**: Continuous surveillance for sepsis warning signs
2. **Analyst Agent 🧬**: Deep clinical reasoning and correlation analysis
3. **Protocol Agent 📋**: Evidence-based treatment protocol generation
4. **Alert Agent 🚨**: Intelligent notification and escalation system

## 📁 Project Structure

```
Hackathon/
├── app.py                 # Flask web application
├── index.py              # Multi-agent AI system
├── dataset.py            # Comprehensive sepsis dataset
├── requirements.txt      # Python dependencies
└── templates/            # HTML templates
    ├── base.html         # Base template
    ├── dashboard.html    # Main dashboard
    ├── patient_input.html # Patient data input
    ├── doctor_review.html # Clinical decision interface
    ├── results.html      # Analysis results
    ├── dataset_explorer.html # Dataset browser
    └── no_analysis.html  # Error page
```

## 🛠️ Installation & Setup

### Prerequisites
- Python 3.8+
- Azure OpenAI API credentials

### Installation

1. **Clone the repository**
   ```bash
   cd /path/to/Hackathon
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure Azure OpenAI credentials**
   - Copy `env.example` to `.env`
   - Update the environment variables with your Azure OpenAI credentials:
     ```bash
     cp env.example .env
     # Edit .env with your actual credentials
     ```

4. **Run the application**
   ```bash
   python app.py
   ```

5. **Access the system**
   - Open browser: `http://localhost:5000`

## 🧪 Testing

### Quick Test Workflow
1. Go to `http://localhost:5000`
2. Click "Dataset" → "Random Case" → "Use for Analysis"
3. Watch the AI agents work in real-time
4. Review results in the doctor interface

### Sample Patient Cases
- **Low Risk**: Viral gastroenteritis, migraine
- **Moderate Risk**: Cellulitis, cholecystitis
- **High Risk**: Pneumonia with sepsis, pyelonephritis
- **Critical Risk**: Post-operative septic shock

## 📊 Dataset

The system includes a comprehensive dataset with:
- **13 Total Cases** across all risk levels
- **Age Range**: 8-89 years (Pediatric to Elderly)
- **10 Teaching Cases** for medical education
- **Real Clinical Scenarios** with known outcomes

## 🎯 User Personas

- **Emergency Department Physicians**: Rapid triage and risk assessment
- **Critical Care Physicians**: Advanced sepsis management
- **Nurses**: Continuous monitoring and early warning
- **Primary Care Physicians**: Decision support and referral guidance
- **Medical Residents**: Educational tool and clinical reasoning
- **Healthcare Administrators**: Quality metrics and compliance

## 🔧 Technology Stack

- **Backend**: Flask (Python)
- **Frontend**: Bootstrap 5, JavaScript
- **AI**: Azure OpenAI GPT-5
- **Architecture**: Multi-agent system with human-in-the-loop
- **Data**: JSON-based dataset with session storage

## 📈 Key Benefits

- **Faster Detection**: AI identifies sepsis earlier than traditional methods
- **Reduced Mortality**: Early intervention saves lives
- **Improved Accuracy**: Multi-agent system reduces false positives/negatives
- **Evidence-Based Care**: Consistent application of latest guidelines
- **24/7 Monitoring**: Continuous surveillance capability
- **Educational Value**: Real-world cases for training and learning

## 🚨 Important Notes

- This is a demonstration system for educational and research purposes
- All AI recommendations require human clinical oversight
- Not intended for direct clinical use without proper validation
- Follow your institution's protocols for sepsis management

## 📞 Support

For questions or issues, please refer to the system documentation or contact the development team.

---

**MedGuard AI - Where AI meets clinical expertise to save lives** 💚

