Sitecore Docker Initial Setup

Prerequries:
Valid Sitecore License File

Docker Desktop
https://doc.sitecore.com/xp/en/developers/100/developer-tools/set-up-the-environment.html


===== DOCKER =====
Open a Powershell CLI and in the root folder run the followings commands
- .\compose-init.ps1
    - Provide the path to the Sitecore license file
    - Provide hostname for your local solution

Build the Solution:
- docker-compose build

Start the Container:
- docker-compose up -d

Stop the Docker Container
- docker-compose stop

Take down the container 
- docker-compose stop

Clean up the local filesystem
- .\docker\clean.ps1


===== Access Sitecore =====
Open a browser and goto: https://cm.[hostname].local/sitecore


===== Sitecore CLI =====
[TODO]