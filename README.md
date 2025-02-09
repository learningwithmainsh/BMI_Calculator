# BMI Calculator 🏋️‍♂️

Welcome to the **BMI Calculator** app! This is a simple health monitoring tool built using **Streamlit** to help you calculate your Body Mass Index (BMI) based on your weight and height.

---

## Features 📊
- Input weight in kilograms.
- Choose height format: centimeters, meters, or feet.
- Calculate your BMI with a single click.
- Get categorized results with health warnings.

---

## Prerequisites 🛠️
Ensure you have **Docker** installed on your system. If not, follow the instructions [here](https://docs.docker.com/get-docker/) to install Docker.

---

## Project Structure 📂
```
.
├── app.py              # Streamlit application code
├── Dockerfile          # Docker configuration file
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation
```

---

## Deployment Steps 🚀

### 1. Clone the Repository
Clone the project to your local machine:

```bash
git clone <repository-url>
cd <repository-directory>
```

### 2. Build the Docker Image
Use the following command to build the Docker image:

```bash
docker build -t bmi-calculator .
```

### 3. Run the Docker Container
Start the container with the following command:

```bash
docker run -p 8501:8501 bmi-calculator
```

### 4. Access the Application 📲💻
Open your web browser and navigate to:

```
http://localhost:8501
```

---

## Customization 🌀
To modify the app, edit the `app.py` file and rebuild the Docker image using the `docker build` command.

---

## Troubleshooting 🚧
- **Docker not found:** Ensure Docker is properly installed and running.
- **Port issues:** Make sure port `8501` is not in use by another application.

---

## License 🌐
This project is open-source and available under the [MIT License](LICENSE).

---

## Author 👤
Created by [Your Name]. Feel free to reach out for any queries or collaborations!

---

Enjoy using the **BMI Calculator** and stay healthy! 🏋️‍♂️💪

