# Expose the Docker API 
## Step 1: Edit /lib/systemd/system/docker.service file
![](images/1.jpg)

## Step 2: Update ExecStart=... -H=tcp://0.0.0.0:2378
![](images/3.jpg)

## Step 3: Reload the daemon and restart the docker service
![](images/1.jpg)
