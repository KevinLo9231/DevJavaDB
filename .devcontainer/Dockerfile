FROM openjdk:11

RUN apt-get update && apt-get install -y \
    maven \
    git \
    curl \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /workspace

ENV JAVA_HOME=/usr/lib/jvm/java-11-openjdk-amd64
ENV PATH=$JAVA_HOME/bin:$PATH

# Check Java and Maven versions
RUN java -version
RUN mvn -version

COPY . /workspace

CMD ["bash"]