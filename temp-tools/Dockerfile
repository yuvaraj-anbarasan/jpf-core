FROM openjdk:10.0.2-jdk

RUN wget --no-check-certificate https://archive.apache.org/dist/ant/binaries/apache-ant-1.10.3-bin.tar.gz \
 && tar -xzvf apache-ant-1.10.3-bin.tar.gz -C /usr/local \
 && rm apache-ant-1.10.3-bin.tar.gz

ENV PATH /usr/local/apache-ant-1.10.3/bin:$PATH

ENTRYPOINT ["bash"]
