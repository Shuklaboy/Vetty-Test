# Vetty Test
 Vetty Assesment Test - Vikas Shukla - shuklaboy452@gmail.com
 # Task 1: Git Basics
  Branch created

# Task 2: Basic Linux Commands 

○ Create a directory named VettyTest. 
    -> mkdir VettyTest
    -> cd VettyTest
    
○ Inside the directory, create a file named script.sh. 
    -> touch script.sh
    
○ Write a script in script.sh to print "Welcome to DevOps!" to the terminal. 
    -> nano script.sh
    
    -> echo "Welcome to DevOps!"
    
○ Make the script executable and run it.
    -> chmod +x script.sh
    -> ./script.sh
 
 ![alt text](<task2.jpg>)
 
 # Task 3: Docker Basics 
1. Create a simple Dockerfile to run an NGINX server. 
○ Use the latest NGINX image. 
○ Expose port 80. 
○ Start the NGINX server in the foreground. 
    -> mkdir nginx-docker
    -> cd nginx-docker
   
Create a Dockerfile
    -> touch Dockerfile
    -> nano Dockerfile
            FROM nginx:latest
            EXPOSE 8080
            CMD ["nginx", "-g", "daemon off;"]

3. Build and run the Docker image. 
    ->docker build -t my-nginx .
    ->docker run -d -p 8080:80 --name nginx-container my-nginx

4. Open the Nginx default page
using web preview in GCP 

![alt text](<task3-1.jpg>)
![alt text](<task3-2.jpg>)






