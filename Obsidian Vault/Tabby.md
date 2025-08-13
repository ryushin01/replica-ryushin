> 운영 서버(kos-was-01) 모니터링
```shell
top -o %MEM
```

> 현행 was 1 모니터링
```shell
cd /home/anbu/logs

ll

tail -f 
// -f 입력 이후 띄어쓰기 한 칸 + Tab 버튼으로 log 선택 
```

> 현행 소켓 데몬 프로세스 여부 확인
```shell
ps -ef | grep Socket_Server_new
```
