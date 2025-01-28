# repo1

sudo wget -O /usr/share/keyrings/jenkins-keyring.asc https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key

echo "deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc]" https://pkg.jenkins.io/debian-stable binary/ | sudo tee /etc/apt/sources.list.d/jenkins.list > /dev/null

sudo apt update
sudo apt install jenkins -y
sudo systemctl start jenkins

sudo apt install -y openjdk-17-jre


sudo systemctl status jenkins

https://github.com/QA-Instructor/lbg-vat-calculator
https://github.com/TheEarlOfGray/simpleflaskapp.git

sudo apt install python3-pip

pip install -r requirements.txt
python3 app.py
