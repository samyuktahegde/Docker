Docker Setup Steps on CentOS 7
First run,
yum update
Then create a file dockerrepo.repo in /etc/yum.repos.d/ with the following contents:
========================================================================================
[dockerrepo] 
name=Docker Repository 
baseurl=https://yum.dockerproject.org/repo/main/centos/7/ 
enabled=1 
gpgcheck=1 
gpgkey=https://yum.dockerproject.org/gpg
========================================================================================


