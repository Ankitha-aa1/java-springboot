Sonarqube Installation:

yum install unzip

adduser sonarqube

passwd sonarqube

su - sonarqube

sudo wget https://binaries.sonarsource.com/Distribution/sonarqube/sonarqube-LATEST_VERSION.zip

unzip *

chmod -R 755 /home/sonarqube/sonarqube-9.4.0.54424

chown -R sonarqube:sonarqube /home/sonarqube/sonarqube-9.4.0.54424

cd sonarqube-9.4.0.54424/bin/linux-x86-64/

./sonar.sh start


