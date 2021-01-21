sudo yum check-update
curl -fsSL https://get.docker.com/ | sh
sudo systemctl start docker
sudo systemctl status docker
sudo systemctl enable docker
sudo getent group docker || groupadd docker
sudo usermod -aG docker $(whoami)
sudo service docker start
