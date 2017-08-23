FROM node:8.2.1

# Create frontend directory
WORKDIR /frontend

# Copy the current directory contents into the container at /frontend
ADD . /frontend

# Install any needed packages specified in package.json
RUN npm install

# Make port 9000 available to the world outside this container
EXPOSE 8000

# Run the command on container startup
CMD npm start
