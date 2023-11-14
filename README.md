# Disease-classification-Using-Deep-Learning-MLOps


# How to run?
### STEPS:

### STEP 01- Clone the repository

```bash
https://github.com/VenkateshL1921/Disease-classification-Using-Deep-Learning-MLOps.git
```
### STEP 02- Create a conda environment after opening the repository and activate it

```bash
conda create -n venv python=3.8 -y
```

```bash
conda activate venv
```


### STEP 03- install the requirements
```bash
pip install -r requirements.txt
```

### STEP 04
```bash
# Run the following command
python app.py
```




# AWS-CICD-Deployment-with-Github-Actions

## 1. Login to AWS console.

## 2. Create IAM user for deployment and give following access
      1. AmazonEC2ContainerRegistryFullAccess
      2. AmazonEC2FullAccess
	
## 3. Create ECR repo to store/save docker image

   	
## 4. Create EC2 machine (Ubuntu) 

## 5. Open EC2 and Install docker in EC2 Machine:

	sudo apt-get update -y

	sudo apt-get upgrade

	curl -fsSL https://get.docker.com -o get-docker.sh

	sudo sh get-docker.sh

	sudo usermod -aG docker ubuntu

	newgrp docker
	
# 6. Configure EC2 as self-hosted runner

# 7. Setup github secrets:

    AWS_ACCESS_KEY_ID=

    AWS_SECRET_ACCESS_KEY=

    AWS_REGION = 

    AWS_ECR_LOGIN_URI = 

    ECR_REPOSITORY_NAME = 
