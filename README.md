# commands-linux-useful.

## 1. List any process listening on any port. 
  ```
    lsof -i:port 
  ```
  1.1 Kill process is listening on any port
  ```
    kill $(lsof -t -i:port)
  ```
## 2. open any folder or file.
  ```
  xdg-open [file/folder name]
  ```
  2.1 open current folder
  ```
  xdg-open . 
  ```
## 3. firewall configuration tool
  ```
  ufw 
  ```
  3.1 list status firewall
  ```
  sudo ufw status
  ```
  3.2 open any port
  ```
  sudo ufw allow 25
  ```
  3.3 block an ip address
  ```
  sudo ufw deny from 155.232.212.143
  ```
