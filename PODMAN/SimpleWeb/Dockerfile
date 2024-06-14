# Specify Base Image
FROM docker.io/node:18-alpine
 
# Work Directory
WORKDIR /usr/app
 	
# Copy our current directory into
# the container
COPY ./ ./

# Install Dependencies
RUN npm install
 
# Startup Command
CMD ["npm", "start"]