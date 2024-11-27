Install docker
```bash
curl -sSL https://get.docker.com/ | sudo sh
sudo usermod -aG docker `whoami`
sudo systemctl start docker.service
sudo systemctl enable docker.service
```

run docker-compose
```bash
sudo docker compose up -d
sudo docket compose start
sudo docker compose ps -a
---------------
fix if timeout
---------------
sudo docker pull prom/prometheus
sufo docker pull grafana/grafana
sudo docker pull prom/alertmanager
```