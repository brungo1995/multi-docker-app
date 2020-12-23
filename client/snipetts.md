# Run Dockerfile.dev
    docker build -t client-img -f Dockerfile.dev .
    docker run -it client-img

# docker compose 
    docker-compose down  && docker-compose up --build