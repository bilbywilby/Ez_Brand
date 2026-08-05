# Contributing to DevHound

Last Updated: 2026-08-05  

Thank you for contributing to DevHound. Review the following requirements prior to opening a pull request.

## 1. Development Environment Setup

### Prerequisites
* JDK 17+ (for Kotlin / KMP modules)
* Node.js 20 LTS (for UI web tooling)
* Python 3.10+ (for validation scripts and CI utilities)
* Docker Engine (for running isolated integration tests)

### Local Build Command

# Clone repository
git clone [https://github.com/bilbywilby/Ez_Brand.git](https://github.com/bilbywilby/Ez_Brand.git)
cd Ez_Brand

# Run validation scripts
python3 validate_funding.py

# Execute test suite
./gradlew check
