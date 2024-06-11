# InterviewQGen
RAG-based interview question and answer generator utilizing the OpneAI GPT model

## Tech stack:
* **Python 🐍:** A versatile programming language that's widely used in web development, data science, automation, and more.
* **LangChain 🔗:** A framework for building applications powered by language models.
* **OpenAI 🤖:** Leveraging state-of-the-art AI models for various applications.
* **FastAPI 🚀:** A modern, fast (high-performance), web framework for building APIs with Python 3.6+ based on standard Python type hints.
* **AWS EC2 ☁️:** Amazon Web Services Elastic Compute Cloud (EC2) provides scalable computing capacity in the cloud, making web-scale cloud computing easier for developers.


## How to run:

1. Create an conda environment with python 3.10

```bash
conda create -n interview python=3.10 -y

```

2. Activate the environment

```bash
conda activate interview

```

### Github Commands 

3. clone the repository

```bash
git clone https://github.com/AmarnathaGowda/InterviewQGen.git
```

4. install requirements

```bash
pip install -r requirements.txt

```

## The Project arctitcture Details :

### The structure of the project as below :

![alt text](https://github.com/AmarnathaGowda/InterviewQGen/blob/main/Doc/InterViewQGen.png)


## wireframe
### Initial :
![alt text](https://github.com/AmarnathaGowda/InterviewQGen/blob/main/Doc/mainpage.png)
### OutPut : 

![alt text](https://github.com/AmarnathaGowda/InterviewQGen/blob/main/Doc/output.png)


# How to Deploy the application on EC2 instance

## 1. Login with your AWS console and launch an EC2 instance

## 2. Run the following commands

### Note: Do the port mapping to this port:- 8080

```bash
sudo apt update
```

```bash
sudo apt-get update
```

```bash
sudo apt upgrade -y
```

```bash
sudo apt install git curl unzip tar make sudo vim wget -y
```

```bash
sudo apt install git curl unzip tar make sudo vim wget -y
```

```bash
git clone "Your-repository"
```

```bash
sudo apt install python3-pip
```
To create the .env file in the instance
```bash
touch .env
```
open and edit the.env file
```bash
vim .env
```
give your OPENAI API KEY and save and close
```bash
:wq
```

To install python on EC2 instance
```bash
sudo apt install python3-venv
```

To create the virtual environment in directory
```bash
python3 -m venv .venv
```

To activate the vertual environment
```bash
python3 -m venv .venv
```
install the requirements
```bash
pip3 install -r requirements.txt
```
run the application
```bash
python app.py
```
