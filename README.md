### docker-discuz (3.2) ###

#### 1. chmod ####
```
chmod 777 * -R

```

#### 2. build docker image ####
```
docker build -t test/discuz .

```

#### 3. start docker container ####

```
docker run --name my-discuz -d -p 8080:80 test/discuz

```

#### 4. install & view discuz ####
```
1) open borwser
   go http://ip:8080/install   to install discuz
   (Mysql username is 'root', password is also 'root')

2) After finished install, go view discuz by http://ip:8080


```