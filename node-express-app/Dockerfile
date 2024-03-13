# Use the official Node.js 14 image as a parent image
FROM node:14

# Set the working directory in the container
WORKDIR /usr/src/app

# Copy the current directory contents into the container at /usr/src/app
COPY . .

# Install any needed packages specified in package.json
RUN npm install

# Make port 5001 available to the world outside this container
EXPOSE 5001

# Run app.js when the container launches
CMD ["node", "app.js"]
