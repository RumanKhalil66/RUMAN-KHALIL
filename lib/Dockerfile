FROM quay.io/maherzubair/sigma-md:beta
RUN git clone https://github.com/Ruman-MD/RUMAN-KHALIL /root/Ruman-MD/RUMAN-KHALIL 
WORKDIR /root/Ruman-MD/RUMAN-KHALIL/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
