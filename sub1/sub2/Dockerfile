FROM alpine
WORKDIR /test
RUN mkdir ./test1
COPY "./sub1/sub2/file.txt" "./test1/"
RUN cat ./test1/file.txt > file1.txt