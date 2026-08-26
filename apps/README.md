# Create env variable

```
vim .env
```

```
DB_NAME=training
DB_HOST=ipaddress
DB_USER=peserta
DB_PASS=password
APP_PORT=3000
```
tesstes

# Sonar-scanner

```
sonar-scanner \
  -Dsonar.projectKey=simple-apps \
  -Dsonar.sources=. \
  -Dsonar.host.url=http://172.23.8.111:9000 \
  -Dsonar.token=sqp_fc3eb694e1fb6f52559c1a3dd856caeb6ac4cb03
  ```