FROM node
WORKDIR /app
RUN npm install meshcentral
VOLUME /app/meshcentral-data
EXPOSE 8080
CMD node node_modules/meshcentral --port 8080 --tlsoffload
