#Poc Java Lambda Serverless API

**Created with serverless framewok**
```
serverless create --template aws-java-gradle --name poc-java-lambda-serverless-api -p poc-java-lambda-serverless-api
```

“Name” parameter specifies the name of the application for Serverless Framework. The “-p” parameter specifies the name of the project root folder.

**Build**

```
./gradlew build
```

**Deploy**

```
serverless deploy
```