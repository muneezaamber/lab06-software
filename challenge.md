1. Install htop: `sudo apt install -y htop` then run `htop`. It shows real-time CPU and memory usage.
2. Version of apache2: `apt show apache2`.
3. Installed packages: `apt list --installed | wc -l`. 
4. Docker Alpine: `sudo docker run --rm alpine echo "Hello from Alpine"`
5. Docker paths: Key is `/etc/apt/keyrings/docker.asc` and sources file is `/etc/apt/sources.list.d/docker.sources`.
6. Remove htop: `sudo apt remove -y htop`, then `hash -r`, then run `htop` to prove it is gone.
