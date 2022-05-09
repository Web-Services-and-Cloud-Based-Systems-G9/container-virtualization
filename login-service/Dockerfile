# Image to which pull from. We are going to use Python 3.8
FROM python:3.8

# Copy the current directory (".") into a directory named "app" that would be in the root of the container
ADD . /app
# Specify the working directory. Any command executed next (RUN/CMD) will be executed inside this directory
WORKDIR /app
# Install dependencies needed for our service
RUN pip install -r requirements.txt
# Expose the port needed to access our service
EXPOSE 8081
# Command line instruction to run our service
CMD ["python3", "./login-service/ShortyLogin.py"]


