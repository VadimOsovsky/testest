FROM node

ARG APP_DIR=/var/www/ocr_pass/ocr
RUN mkdir -p ${APP_DIR}
WORKDIR ${APP_DIR}

COPY package*.json ./
RUN npm i
COPY . .
