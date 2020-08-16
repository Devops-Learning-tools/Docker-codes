Docker Installation

	1. Install yum-utils
# yum install -y yum-utils

	2. Add docker repo
# yum-config-manager --add-repo https://download.docker.com/linux/centos/docker-ce.repo

	3. Enable Docker repo  
# yum-config-manager --enable docker-ce-nightly
  
	4. Test repo
# yum-config-manager --enable docker-ce-test

	5. Disable the repo
# yum-config-manager --disable docker-ce-nightly

	6. Docker packages install
# yum install docker-ce docker-ce-cli containerd.io

	7. Start docker service
#  systemctl start docker

	8. Run hello-world
# docker run hello-world

