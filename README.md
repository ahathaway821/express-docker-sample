# Build the image:
docker build -t ahathaway821/express-docker-sample .

# Run the image:
docker run -p 49160:8080 -d ahathaway821/express-docker-sample