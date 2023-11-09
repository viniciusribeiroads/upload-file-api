Para fazer upload:
curl -x POST -F "file@=arquivo.jpeg" http://localhost:8080/api/files/upload

Para listar:
curl http://localhost:8080/api/files/list