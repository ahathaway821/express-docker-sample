# Build the image:
docker build -t <your username>/node-web-app .

# Run the image:
docker run -p 49160:8080 -d <your username>/node-web-app