FROM node
ENV REACT_APP_BACKEND_URL http://localhost:8080
EXPOSE 5000
COPY . . 

RUN npm install -g serve
RUN npm install
RUN npm run build

CMD [”serve", "-s", "-l", "5000", "build"]
