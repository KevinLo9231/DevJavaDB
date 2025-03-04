FROM openjdk:11

RUN apt-get update && apt-get install -y \
    maven \
    git \
    curl \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /workspace

ENV JAVA_HOME=/opt/java/openjdk

COPY . /workspace

CMD ["bash"]