FROM gcc:4.8
COPY . /usr/src/c_test
WORKDIR  /usr/src/c_test
RUN gcc -o Test main.c
CMD [ "./Test" ]