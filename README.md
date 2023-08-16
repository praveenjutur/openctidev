1. Source: https://www.linkedin.com/pulse/opencti-installation-howto-daniel-bender
1. Start Portainer:```docker run -d -p 18000:8000 -p 19000:9000 --name=portainer --restart=always -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data portainer/portainer-ce```
