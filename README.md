Build container:
```
cd ~/Projects/it_one_cup_java_2022
docker build -t my_local_quickstart .
```
Run container locally:
```
docker run -d -p 9081:9081 my_local_quickstart
```