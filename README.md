# **DOCKER BASICS**  

In my first Docker project, I started by printing **"Hello, World!"**.  

## **Creating the Application File**  
First, we create a Python file named **`app.py`**.  

---

## **Documentation**  
Here are some useful references for Docker:  
1. [Official Docker Documentation](https://docs.docker.com/)  
2. [Docker Desktop Guide](https://docs.docker.com/desktop/)  

---

## **Deployment**  

To deploy a basic application using Docker, follow these steps:  

### **Step 1: Install Docker and Python**  
1. Download and install **Docker Desktop** from [here](https://www.docker.com/products/docker-desktop/).  
2. Ensure that Docker is running.  
3. Install the required **Docker** and **Python** extensions in your development environment.  

### **Step 2: Verify Installation**  
Before proceeding, confirm that both **Docker** and **Python** are installed by running the following commands:  

Check Docker version:  
```bash
docker --version 
```  

Check Python version:  
```bash
python --version 
```  

If both commands return valid versions, you are ready to proceed.  

---

### **Step 3: Build and Run the Docker Application**  

#### **i) Build the Docker Image**  
Use the following command to build your Docker image:  
```bash
docker build -t myapp .
```  

#### **ii) Verify the Image Creation**  
Once the build is complete, check if the Docker image was created successfully:  
```bash
docker images
```  

#### **iii) Run the Docker Container**  
Now, execute the container to print **"Hello, World!"** in the console:  
```bash
docker run myapp
```  

---

This guide provides a clear and structured approach to running your first Dockerized Python application. 🚀  
