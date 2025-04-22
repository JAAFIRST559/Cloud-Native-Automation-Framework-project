
# Cloud-Native Automation Framework

A modular automation framework designed for end-to-end testing of web and API applications. This project integrates Selenium for UI automation, RestAssured for API testing, and TestNG for test orchestration. Built with CI/CD compatibility using GitHub Actions and Jenkins.

# Cloud-Native Toolkit

The Cloud-Native Toolkit is a comprehensive collection of tools and frameworks that support the entire lifecycle of cloud-native applications, from design to deployment.

## 🌐 Official Website

Visit the official site for complete documentation and resources:  
🔗 [https://cloudnativetoolkit.dev](https://cloudnativetoolkit.dev)

## 📦 Key Features

- Streamlines cloud-native development workflows
- Provides reusable patterns and automation solutions
- Supports continuous integration and delivery
- Compatible with multiple cloud platforms and DevOps tools
- Enables faster, more consistent application delivery

## 🛠️ Components

- **Automation Tools**: Templates and scripts for CI/CD
- **DevOps Integration**: Jenkins, Tekton, GitHub Actions
- **Deployment Support**: Kubernetes, OpenShift, GCP, AWS
- **Developer Experience**: Pre-configured IDEs, linting, testing support

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
