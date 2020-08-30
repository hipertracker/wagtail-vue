FROM node:12.15.0 as base

WORKDIR /code/cms/frontend
COPY ./package.json /code/cms/frontend
RUN yarn install
COPY ./ /code/cms/frontend
