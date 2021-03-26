FROM node
WORKDIR /app
RUN npm install meshcentral
VOLUME /app/meshcentral-data
EXPOSE 8080
EXPOSE 443
EXPOSE 4433
CMD node node_modules/meshcentral
