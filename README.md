# Cloud-Native Automation Framework

A modular automation framework designed for end-to-end testing of web and API applications. This project integrates Selenium for UI automation, RestAssured for API testing, and TestNG for test orchestration. Built with CI/CD compatibility using GitHub Actions and Jenkins.

## 🔧 Features

- UI automation with Selenium WebDriver
- API testing using RestAssured
- Test orchestration with TestNG
- Automated reporting via Extent Reports
- CI/CD pipeline integration using GitHub Actions and Jenkins
- Scalable and modular architecture

## 📁 Folder Structure

```
cloud-native-automation-framework/
├── src/
│   ├── test/
│   │   ├── java/
│   │   │   ├── base/
│   │   │   ├── tests/
│   │   │   └── utils/
├── testng.xml
├── pom.xml
├── Jenkinsfile
└── .github/
    └── workflows/
        └── ci.yml
```

## 🚀 Getting Started

### Prerequisites

- Java 11+
- Maven 3.6+
- GitHub CLI or Jenkins (optional for CI/CD)

### Run Tests Locally

```bash
git clone https://github.com/JAAFIRST559/cloud-native-automation-framework.git
cd cloud-native-automation-framework
mvn clean test
```

## 📊 Reporting

Test results are generated automatically using Extent Reports and stored in the `/reports` folder after execution.

## 🧪 CI/CD Integration

- GitHub Actions: `.github/workflows/ci.yml` runs tests on every push or pull request.
- Jenkins: Configured with `Jenkinsfile` for build automation.

## 🤝 Contributing

Feel free to fork this repository and raise a pull request with enhancements or bug fixes!

## 📄 License

This project is licensed under the MIT License.
