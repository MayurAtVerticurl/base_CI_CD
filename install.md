# Install Jenkins in Ubuntu 20.04 

- Install Java JDK & Maven 

        https://www.hostinger.in/tutorials/how-to-install-maven-on-ubuntu

- Install Jenkins

        https://www.jenkins.io/doc/book/installing/linux/#debianubuntu

- Command to retrive Admin Passwd

        sudo cat /var/lib/jenkins/secrets/initialAdminPassword

- install Docker 

        https://docs.docker.com/engine/install/ubuntu/#install-using-the-convenience-script

- Running SonarQube in a Docker Container

    SRC : https://docs.sonarsource.com/sonarqube/latest/setup-and-upgrade/install-the-server/installing-sonarqube-from-docker/

        docker run -d --name sonarqube \
        -p 9000:9000 \
        -v sonarqube_data:/opt/sonarqube/data \
        -v sonarqube_extensions:/opt/sonarqube/extensions \
        -v sonarqube_logs:/opt/sonarqube/logs \
        sonarqube:lts-community

    ### Sonar Credentials 

    Username : `admin`

    Default Password : `admin`

    new Password : `admin@123`