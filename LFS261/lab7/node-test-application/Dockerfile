# Choose Node image
FROM node:16 

# Set our working directory on the container
WORKDIR /app 

# COPY all the files from Current Directory into the container working directory
COPY . . 

# Install the Project Dependencies with npm
RUN npm install 

# Tell that this image is going to Open a Port
EXPOSE 8080 

# Command to launch the Application
CMD ["npm", "start"]
