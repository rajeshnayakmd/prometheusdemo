
# To montior Docker runtime 

## add /etc/docker/daemon.json with bellow content
    {
    "metrics-addr" : "0.0.0.0:9091",
    "experimental" : true
    }

## restart Docker service 
# sudo systemctl restart docker

# TODO 
# data persistancy 

