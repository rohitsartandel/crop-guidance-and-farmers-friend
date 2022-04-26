The Agriculture sector is the backbone of our country.It provides a living
for the vast majority of India’s inhabitants, but it only accounts for 15%
of the country’s GDP. In comparison to other countries, our country’s crop
yield is quite poor. This could be one of the reasons for India’s increased
suicide rate among marginal farmers. Another cause for this is that farmers
do not plan their crops properly.Another reason for this situation is that
farmers frequently make incorrect crop selection decisions, such as planting
in the wrong season or picking a crop that would not yield much for the
particular soil. Incorrect crop selection will always result in a lower yield. It
is difficult to survive if the family is entirely dependent on this revenue. In
this paper, we offer a model that addresses these concerns.



Ansible installation:
$ sudo apt update 
$ sudo apt install software-properties-common 
$ sudo add-apt-repository --yes --update ppa:ansible/ansible 
$ sudo apt install ansible
$ apt-get purge ansible  //uninstall
sudo apt-get install git				 //install
sudo apt-get remove --auto-remove git 	//uninstall



//git push

mkdir devops
Cd devops
Git init
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
nano print.py , enter command , c+x , yes
Git add .
Git status
Git commit -m “message”
Git remote add origin “https://github.com/abcd/devops_trial.git”
Git push -u origin main/master

// git_pull

mkdir devops
Cd devops
git init
Git remote add origin <link>
Git pull origin <branch>

// Git_config

mkdir devops
Cd devops
Git init
Git config user.email “<email>”
Git config user.name “<name>”
Ls -al
Cd .git
Ls -al
Cat config



// git log

mkdir devops
Cd devops
Git init
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
nano print.py , enter command , c+x , yes
Git add .
Git status
Git commit -m “message”
git log


Installing docker
Sudo apt-get install docker.io
sudo systemctl status docker //check if running or not
Docker run hello-world //check if installation is done correctly or not

Docker rm container id           //to remove container
Docker rmi imageid              // to remove images

Docker Pull 
Sudo bash
Docker images
Docker pull ubuntu
Docker images
(optional)
Docker run -itd ubuntu
Docker ps
Docker exec -it <container-id> bash

Docker Push
Docker images
Docker run -itd ubuntu
Docker ps
Docker exec -it <container-id> bash
(inside ubuntu)
Echo abcd>newfile
Cat newfile
Exit
(outside)
Docker ps
Docker commit <conatiner-id> new
docker tag SOURCE_IMAGE[:TAG] dockerusername/TARGET_IMAGE[:TAG]
Docker tag new:latest <username>/dickshant:pussy
Docker login
Docker images
Docker push <username>/dickshant:pussy


Deploy
mkdir devops
cd devops
Nano app.py
Print(“Welcome Docker file”)
nano dockerfile (//Below 3 lines under dockerfile)
FROM python
COPY . /src
CMD ["python", "/src/app.py"]
sudo bash
docker build . -t python_app
docker run python_app





 Installation of Jenkins
Sudo apt-get update
Sudo apt-get -y upgrade
Sudo apt install openjdk-11-jdk

  curl -fsSL https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo tee \
    /usr/share/keyrings/jenkins-keyring.asc > /dev/null

  echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \
    https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
    /etc/apt/sources.list.d/jenkins.list > /dev/null

 sudo apt-get update

sudo apt-get install jenkins


