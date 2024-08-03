In this directory 3 files are there. 
docker-repo-automation.sh is the file which automating the docker-repo creation (blacklog- password should set manually).
docker-repo-delete.sh is the, deleting docker-repo. Here I commented the certificat delete(as per the need uncommand). 
before using delete script,(sudo unlink /etc/nginx/sites-enabled/$domain_name.conf) then run delete script. 
sudo rm -rf registry

Here docker-repo-https-working is the script will create the docker repo but some user input is required.
