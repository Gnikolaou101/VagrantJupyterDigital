https://github.com/devopsgroup-io/vagrant-digitalocean

1) Install vagrant 
2) Install plug in with the command vagrant plugin install vagrant-digitalocean
3) Put your access token for your own digital ocean account
3) do `vagrant up` to create and provision the droplet
4) add a firewall to the drop with open inbound tcp port 8987
5) visit <droplet_ip>:8987 to access jupyter. Token is "token".
