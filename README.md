# MP02-SE4367.001
## Instrumenting Android Apps with Soot

### Part 1
#### Changing NetID in AndroidInstrument.java
![image](https://user-images.githubusercontent.com/60763350/116766959-dffcd280-a9f2-11eb-865a-dc3ccacf464d.png)

To Run AndroidInstrument:
1. Have Soot.jar in Referenced (External) Libraries
2. Download Android libraries from https://github.com/Sable/android-platforms as 'android-platforms'.
3. Download 'sq3.apk'.
4. Run As > Run Configurations > Arguments 
5. Under Program Arguments insert:
-android-jars {path-to-android-platforms} -process-dir {path-to-sq3.apk}

### Part 2
#### Keytool Step(s):
![image](https://user-images.githubusercontent.com/60763350/116766904-9613ec80-a9f2-11eb-9554-6a31c8eccdb8.png)

#### ZipAlign Step(s):
![image](https://user-images.githubusercontent.com/60763350/116766942-c196d700-a9f2-11eb-806c-bfc4d064ba20.png)

So far, files generated include the my.keystore file and the new aligned apk:\
![image](https://user-images.githubusercontent.com/60763350/116768019-569cce80-a9f9-11eb-9e8c-11e36d028abd.png)

The aligned generated apk file will be uploaded to the Github repo as 'sq3-aligned.apk'.

### Part 3
#### JarSigner:
![image](https://user-images.githubusercontent.com/60763350/116767828-3a4c6200-a9f8-11eb-942b-4d882fa7a96b.png)

#### JarSigner Verification:
![image](https://user-images.githubusercontent.com/60763350/116767899-a4fd9d80-a9f8-11eb-896d-b1c631d2e58d.png)
