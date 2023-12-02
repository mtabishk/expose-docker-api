# Expose the Docker API (un-encrypted)
[![Watch the video](https://img.youtube.com/vi/ipECJ18UPwg/maxresdefault.jpg)]([https://youtu.be/vt5fpE0bzSY](https://youtu.be/ipECJ18UPwg))
## Step 1: Edit /lib/systemd/system/docker.service file
![](images/1.jpg)

## Step 2: Update ExecStart= ... -H=tcp://0.0.0.0:2378
![](images/3.jpg)

## Step 3: Reload the daemon and restart the docker service
![](images/1.jpg)
