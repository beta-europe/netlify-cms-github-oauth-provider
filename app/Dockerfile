# Netlify-cms-github-oauth-dockerised
# This dockerised version is based off vencax/netlify-cms-github-oauth-provider

FROM node:latest

# Node:latest is used as a base image because it surely has all the necessary dependencies

RUN git clone https://github.com/beta-europe/netlify-cms-oauth-dockerised.git
WORKDIR netlify-cms-oauth-dockerised 
RUN npm install
