# 使用 Java 11 作為基礎映像
FROM openjdk:11

# 設定工作目錄
WORKDIR /workspace

# 複製當前目錄內容到容器內部
COPY . /workspace

# 執行 Java 程式的命令
CMD ["java", "-jar", "myapp.jar"]
