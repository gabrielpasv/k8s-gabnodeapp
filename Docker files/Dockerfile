FROM node:boron

# Create app directory
WORKDIR /gab-node-app

# Clone repo
RUN git clone https://github.com/gabrielpasv/gab-node-app.git .

# Install Dependencies 
RUN npm install


EXPOSE 80
CMD [ "npm", "start" ]