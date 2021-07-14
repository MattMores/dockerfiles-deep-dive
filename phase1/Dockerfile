# Project: Extend an existing official image from Docker Hub to run a webserver

# Step 1: Use the 'nginx' official image, with the latest version for alpine
#   Pinning a version makes development so much easier because it is predictable
FROM nginx:1.21.1-alpine
EXPOSE 80
WORKDIR /usr/share/nginx/html
COPY /index.html /usr/share/nginx/html/

# Step 2: Change our working directory to the root of nginx webhost
#   Using 'WORKDIR /some/path' is preferred to using 'RUN cd /some/path'

# Step 3: Copy in the file or files or folder!

# No need to specify EXPOSE or CMD because they're include in the base (FROM)


#  RUN apt-get update \
#     && apt-get install --no-install-recommends



# FROM node:15-alpine3.10
# EXPOSE 3000
# WORKDIR /app
# COPY package.json package-lock.json /app/
# RUN nmp install
# COPY . .
# CMD ["npm", "start"]
