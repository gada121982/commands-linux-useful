# commands-linux-useful
I list all commands linux that help your life easier :3

1. List any process listening on any port. 
```
  lsof -i:port 
```
1.1 Kill process is listening on any port
```
  kill $(lsof -t -i:port)
```

2. open any folder or file
```
xdg-open [file/folder name]
```
2.1 open current folder
```
xdg-open . 
```
