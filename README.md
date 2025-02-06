ngrok alternative https://localhost.run/
ngrok free alternative ssh reverse https://docs.google.com/document/d/1KN-dtut2Re5vu9lEHmTGJqS2yNMM-Q4_cbJDQd041Vg/

docker sudo permission denied
```
sudo usermod -aG docker $USER
newgrp docker
```

gerenciar multiplos nodejs
```
npm i -g pm2
```
```
pm2 start npm --name "myapp" -- run start
```
```
pm2 logs
```
```
pm2 remove myapp
```
```
pm2 save
pm2 startup
```
