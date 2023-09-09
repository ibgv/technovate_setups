## Setting Up DVWS-Node

Follow these steps to set up DVWS-Node on your VM:

### Step 1: Install docker-compose
Commands 

```
sudo curl -L "https://github.com/docker/compose/releases/download/v2.21.0/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
docker-compose --version
```


### Step 2: DVWS-Node Repository

Clone the DVWS-Node repository by running the following command in your VM's terminal:

```
git clone https://github.com/snoopysecurity/dvws-node.git

cd dvws-node

docker-compose up
```

