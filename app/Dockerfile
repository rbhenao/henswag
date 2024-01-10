# Use a base image with Node.js pre-installed
FROM swaggerapi/swagger-ui:latest

#Copy all of the app contents into the app dir
COPY ./ /app

# Expose the default Swagger UI port (change if necessary)
EXPOSE 8080

# Command to start the Swagger UI
CMD nginx -g "daemon off;"
