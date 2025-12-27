# 🐳 Dockerized Static Website with Nginx

This project demonstrates how to serve a static website using **Nginx** inside a **Docker container** based on the lightweight `nginx:alpine` image.

## 📌 Overview

- ⚡ Uses `nginx:alpine` for minimal image size and fast startup  
- 📁 Static files are copied into Nginx’s default web root  
- 🔌 Container port **80** is mapped to host port **8080**  
- 🌐 Suitable for simple static websites (HTML, CSS, JS)

## 🛠 Tech Stack

- 🐳 Docker  
- 🌐 Nginx (Alpine Linux base image)  
- 📄 Static Web Files (HTML)

## 📂 Project Structure


├── Dockerfile
├── index.html
└── README.md

#### Build the Docker Image
   docker build -t static-nginx-site .

#### Run the Container
docker run -d -p 8080:80 static-nginx-site   

#### Access the Website

Open your browser and visit:

http://localhost:8080

