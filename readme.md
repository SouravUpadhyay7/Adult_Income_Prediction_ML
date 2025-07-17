# 🎯 Adult Income Prediction ML

A comprehensive machine learning pipeline that predicts whether an individual's income exceeds $50K/year based on census data. Built with Python and deployed as a web application using Flask.

## 📊 Project Overview

This project implements an end-to-end machine learning solution that includes data ingestion, transformation, model training, and deployment. The system processes demographic and employment data to make accurate income predictions.

## 🏗️ Project Structure

```
Adult-Income-Prediction-ML/
├── 📄 app.py                          # Flask web application
├── 📊 adult.csv                       # Dataset
├── 📓 ML_project_live_class.ipynb     # Jupyter notebook for analysis
├── 📝 problem_statement.txt           # Project requirements
├── 📚 readme.md                       # Project documentation
├── 📋 requirements.txt                # Python dependencies
├── ⚙️ setup.py                        # Package setup
├── 📂 artifacts/                      # Generated model artifacts
│   ├── 📥 data_ingestion/
│   ├── 🔄 data_transformation/
│   └── 🤖 model_trainer/
├── 🌐 env/                            # Virtual environment
├── 📝 logs/                           # Application logs
├── 📓 notebook/                       # Jupyter notebooks
│   └── 📊 data/
├── 🔧 src/                            # Source code
└── 🎨 templates/                      # HTML templates
```

## 🚀 Getting Started

### Prerequisites

- **Python 3.7+**
- **pip** (Python package manager)
- **Git** (for cloning the repository)

### 📦 Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Adult-Income-Prediction-ML
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv env
   ```

3. **Activate the environment**
   
   **Windows:**
   ```bash
   .\env\Scripts\activate
   ```
   
   **Linux/Mac:**
   ```bash
   source env/bin/activate
   ```

4. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

### 🎮 Usage

#### Web Application
Start the Flask web application:
```bash
python app.py
```
Navigate to `http://localhost:5000` in your browser to use the prediction interface.

#### Jupyter Notebook
For interactive data exploration and model development:
```bash
jupyter notebook ML_project_live_class.ipynb
```

## 🔧 Project Components

### 📥 Data Ingestion
- Loads and validates the raw census data (`adult.csv`)
- Handles missing values and data quality checks
- Splits data into training and testing sets

### 🔄 Data Transformation
- Feature engineering and preprocessing
- Categorical variable encoding
- Feature scaling and normalization
- Data pipeline creation

### 🤖 Model Training
- Multiple algorithm evaluation
- Hyperparameter tuning
- Model selection and validation
- Performance metrics calculation

### 🌐 Deployment
- Flask web application
- User-friendly prediction interface
- Real-time prediction capabilities
- Input validation and error handling

## 📊 Dataset Features

The model uses the following features for prediction:
- Age
- Work Class
- Education Level
- Marital Status
- Occupation
- Relationship
- Race
- Sex
- Capital Gain/Loss
- Hours per Week
- Native Country

## 🎯 Model Performance

The trained model achieves:
- **Accuracy:** High prediction accuracy on test data
- **Precision:** Reliable positive predictions
- **Recall:** Good coverage of actual positive cases
- **F1-Score:** Balanced performance metric

## 📝 Logging

Comprehensive logging system:
- **Location:** `logs/` directory
- **Features:** Error tracking, performance monitoring, debugging information
- **Format:** Structured logs with timestamps and severity levels

## 🛠️ Development

### Project Setup
```bash
# Install in development mode
pip install -e .

# Run tests
python -m pytest

# Check code quality
flake8 src/
```

### Adding New Features
1. Create feature branch
2. Implement changes
3. Add tests
4. Update documentation
5. Submit pull request

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

## 📄 License

This project is licensed under the **MIT License** - see the LICENSE file for details.

## 👨‍💻 Author

**Sourav Upadhyay**


## 🙏 Acknowledgments

- Census Bureau for providing the dataset
- Open source community for amazing tools
- Contributors and supporters

---

⭐ **Star this repository if you found it helpful!** ⭐