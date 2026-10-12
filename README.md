# Python Flask Application Deployment Using Jenkins on AWS EC2

## 📌 Project Overview

This project demonstrates the deployment of a Python Flask web application on an AWS EC2 instance using Jenkins and webhook integration.

The application was developed using Python and Flask and hosted on an EC2 virtual server. Jenkins was used as part of the deployment workflow, and a webhook was configured to support automated deployment triggers.

The deployed application was accessed through a web browser using the server's public IP address and port `5000`.

## 🎯 Objectives

- Deploy a Python Flask application on AWS EC2.
- Configure the Linux server environment to run the application.
- Install the required Python dependencies.
- Integrate Jenkins into the deployment workflow.
- Configure a webhook for deployment automation.
- Verify the deployed application through a web browser.

## 🛠️ Technologies Used

- **Python** – Application development.
- **Flask** – Python web application framework.
- **AWS EC2** – Cloud-based virtual server.
- **Jenkins** – Automation and deployment workflow.
- **Webhook** – Event-based trigger for automation.
- **Linux** – Server environment and command-line administration.
- **pip** – Python package installation.
- **Gunicorn** – WSGI server command used during deployment testing.

## ⚙️ Project Implementation

### 1. AWS EC2 Setup

Created and accessed an EC2 instance to host the Python application.

### 2. Python Environment Setup

Prepared the Python project directory and installed the required dependencies using the project's `requirements.txt` file.

The project directory contained:

- `app.py`
- `requirements.txt`
- `myvenv/`

### 3. Flask Application Execution

Ran the Flask application using:

```bash
sudo python3 app.py
```

The application listened on port `5000` and was configured to accept connections on all network interfaces.

### 4. Jenkins and Webhook Integration

Integrated Jenkins into the deployment workflow and configured a webhook to support automated triggering of the deployment process.

### 5. Deployment Verification

Opened the application through a web browser using the EC2 public IP address and port `5000`.

The deployed page displayed the confirmation message:

**"successfully deployed python application through jenkins, added webhook"**

This confirmed that the web application was accessible through the browser.

## 🚀 Key Features

- Python-based web application.
- Flask application framework.
- Deployment on AWS EC2.
- Jenkins-based deployment workflow.
- Webhook integration.
- Browser-based deployment verification.

## 📸 Project Screenshots

Add your screenshots to a folder named `screenshots` in the repository.

Suggested screenshots:

1. `python-app-output.png` – Deployed Flask application in the browser.
2. `python-ec2-terminal.png` – Flask application running on the EC2 instance.

Display them in this section using:

```markdown
![Python Application Output](screenshots/python-app-output.png)

![Python EC2 Deployment](screenshots/python-ec2-terminal.png)
```

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Deploying Python applications on AWS EC2.
- Running Flask applications on a Linux server.
- Managing Python dependencies.
- Working with Jenkins and webhook integration.
- Understanding cloud application deployment.
- Testing application accessibility through a browser.

## 🔮 Future Enhancements

- Configure a production-ready WSGI server.
- Automate testing and deployment through a complete CI/CD pipeline.
- Configure HTTPS and a domain name.
- Add application logging and monitoring.
- Improve application error handling.

## ✅ Conclusion

This project provided hands-on experience in deploying a Python Flask application on AWS EC2 and integrating Jenkins with webhook-based automation.

The application was successfully accessed through a web browser, demonstrating the practical use of cloud infrastructure, Python web development, and deployment automation.

---

**Project Type:** Python Web Application Deployment  
**Language:** Python  
**Framework:** Flask  
**Cloud Platform:** AWS EC2  
**Automation Tool:** Jenkins  
**Integration:** Webhook
