# Deploying This Project to AWS Elastic Beanstalk

This project can be deployed to **AWS Elastic Beanstalk** using a ZIP file of the application source code.

## 📦 Create a Deployment ZIP File

Follow these steps to create the deployment ZIP:

### 1. Clone the Repository

```bash
git clone https://github.com/SkyOps-Dev/elastic-beanstalk-tutorial-.git
```

### 2. Navigate to the Project Directory
```bash
cd my-app
```

### 3. Create a ZIP File (Excluding .DS_Store)
```bash
zip -r ../my-app.zip . -x "*.DS_Store"
```

### 4. Go Back to the Parent Directory
```bash
cd ../
```

After running these commands, your directory structure should look like this:

```bash
.
├── my-app
└── my-app.zip
```