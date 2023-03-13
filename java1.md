## java编译 打包

javac -d bin src/main/*.java src/com/*/*/*.java
java -cp bin/ main.Main

cd bin
jar -cef  main.Main ../a.jar com/ main/
