# MLOps - End to End Continuous Integration

This repository serves as a practical guide to understanding and implementing end-to-end Continuous Integration (CI) within the realm of Machine Learning Operations (MLOps). It demonstrates how to automate testing, validation, and deployment of ML pipelines using GitHub Actions.

## 🚀 Project Overview

The primary objective of this project is to showcase the integration of CI practices in MLOps workflows. By leveraging GitHub Actions, the repository automates the process of testing and validating machine learning models, ensuring that code changes do not break existing functionalities.

## 📁 Repository Structure

```bash
Mlops-Continous-Integration/
├── .github/
│   └── workflows/
│       └── ci.yml             # GitHub Actions workflow for CI
├── app.py                     # Main application script
├── _test.py                   # Unit tests for the application
├── requirements.txt           # Python dependencies
├── CI-Notes.pdf               # Documentation on CI concepts
├── LICENSE                    # MIT License
└── README.md                  # Project documentation
```

## ⚙️ Getting Started

### Prerequisites

- Python 3.8 or higher  
- Git  
- GitHub account  

### Installation

1. **Clone the repository:**

```bash
git clone https://github.com/Anand21J-V/Mlops-Continous-Integration.git
cd Mlops-Continous-Integration
```

2. **Create a virtual environment:**

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies:**

```bash
pip install -r requirements.txt
```

## 🧪 Running Tests

To execute unit tests and ensure that all components are functioning correctly:

```bash
pytest _test.py
```

## 🔄 Continuous Integration with GitHub Actions

The repository utilizes GitHub Actions to automate the CI process. The workflow is defined in `.github/workflows/ci.yml` and is triggered on every push or pull request to the `main` branch.

**Workflow Steps:**
1. **Checkout Code:** Retrieves the latest code from the repository.  
2. **Set Up Python:** Configures the Python environment.  
3. **Install Dependencies:** Installs required Python packages.  
4. **Run Tests:** Executes unit tests to validate code changes.  

This setup ensures that any code changes are automatically tested, promoting code reliability and facilitating collaboration.

## 📄 Documentation

- **CI-Notes.pdf:** Provides an in-depth explanation of Continuous Integration concepts and their application in MLOps.

## 👨‍💻 Author

**Anand Kumar Vishwakarma**

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🙌 Acknowledgements

This project is inspired by best practices in MLOps and Continuous Integration.  
For a deeper understanding, consider exploring resources on [CI/CD in MLOps](https://www.geeksforgeeks.org/continuous-integration-and-continuous-deployment-ci-cd-in-mlops/).
