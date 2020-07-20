FROM node

ARG APP_DIR=/var/www/ocr_pass/web_app
RUN mkdir -p ${APP_DIR}
WORKDIR ${APP_DIR}

COPY package*.json ./
RUN yarn install
COPY . .
