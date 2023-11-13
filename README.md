# CSE110 Lab 2!

## How to run
```
git pull
```
Make sure to clear Java workspace and restart VSCode. Make sure to run the server first. To run the server, do:

```
cd src/main/java
javac -cp ".:/path/to/your/json-20230227.jar" server/*.java
java -cp ".:/path/to/your/json-20230227.jar" server/Server
```

Then, open a new terminal and run the app by:
```
./gradlew run
```

To run tests, do:
```
./gradlew build
```

## GitHub
Pull code
```
git pull
```
Change branch
```
git checkout branchname
```
Make new branch
```
git checkout -b newbranch
```
Add updates/modifications to files
```
git add /file/path/
```
Commit locally
```
git commit -m "Commit message with issue #"
```
Push to remote repository
```
git push
```
