# LoadBalancer controllers/defaults  

## Install
1. Download `haproxy` or `nginx`
2. `tar xzf *.tar.gz` to unpack them (replace the * with the package name so it doesn't unpack every tar.gz in the directory)
3. `cd` into the unpacked directory
4. `git remote add https://github.com/gabeio/loadbalancer` 
5. `git pull` to get the stuff you need
6. `git checkout` `nginx` or `haproxy` depending on the situation.  
7. `./new` adds packages for ubuntu which are needed to build.
8. Run the `./fix` to allow nginx/haproxy to connect to ports lower than 1024 without sudo.  
9. Use `start`/`stop`/`restart` without sudo or root & enjoy.  

## pull requests are welcome
If you have a better way to isolate nginx/haproxy for killing,  
**I would be greatly appreciative of pull requests to improve them.**  
