FROM node:8.2.1

# Create backend directory
WORKDIR /backend

# Copy the current directory contents into the container at /backend
ADD . /backend

# Install any needed packages specified in package.json
RUN npm install

# Make port 9000 available to the world outside this container
EXPOSE 9000

# Run the command on container startup
CMD npm start
