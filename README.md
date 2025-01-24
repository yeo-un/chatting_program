# chatting_program
c로 만든 채팅 프로그램 

#### 개발환경: MAC OS

## server
```
gcc server.c -o server
```
### 서버 실행
```
./server <port number>   (ex) ./server 9999
```

## client
```
gcc client.c -p client
```

### 클라이언트 실행
```
./client <ip> <port number> <nickname>    (ex) ./client 127.0.0.1 9999 test1
```
