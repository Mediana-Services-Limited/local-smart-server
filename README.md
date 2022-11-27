# local-smart-server
настройка лкального сервера

1. Запускается lampp.service
path-service /etc/systemd/system/xampp.service

2. Запускается smartserve.service
path-service /etc/systemd/system/smartserve.service
path-sh      /usr/bin/smartserve.sh

3. Запускается nodesocket.service
path-service /etc/systemd/system/nodesocket.service
path-sh      /usr/bin/nodesocket.sh
