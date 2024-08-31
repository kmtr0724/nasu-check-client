ヘルスチェック用クライアント  
pyを/usr/local/bin/にコピー  
.serviceを/usr/lib/systemd/system/　に配置  
```
systemctl daemon-reload  
systemctl start health_check_bme280.service
```
