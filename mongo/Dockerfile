FROM mongo:latest
WORKDIR /usr/local/app

# 27017 is Mongo's default port
EXPOSE 27017

# Create and use a non-root user
RUN useradd app
USER app
