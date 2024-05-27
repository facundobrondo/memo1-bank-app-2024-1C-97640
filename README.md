# memo1-bank-app
Memo1 - Backend API

## Dependencies
Java is required. Check version with `java -version`. 
For installation:
```
sudo apt update
```
Install OpenJDK 11
```
sudo apt install openjdk-11-jdk
```

Configure
```
export JAVA_HOME=/usr/lib/jvm/java-11-openjdk-amd64
export PATH=$JAVA_HOME/bin:$PATH
source ~/.bashrc

```
## Running
For run the application

```
./gradlew build
```

Then
```
./gradlew bootRun
```

And you can open the interface
```
http://localhost:8080/swagger-ui.html
```





