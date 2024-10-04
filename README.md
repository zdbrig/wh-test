# wh-test


## Running the Project

Follow these steps to set up and run the project:

1. Generate requirements file:
   ```
   pipreqs . --force
   ```

2. Build the Docker image:
   ```
   docker build -t wh-project .
   ```

3. Run the Docker container:
   ```
   docker run -p 8080:5000 -it wh-project
   ```

This will start the application and map port 8080 on your host to port 5000 in the container.



![image](https://github.com/user-attachments/assets/eb2ffffb-e943-4a22-8d13-c287b412f19c)

