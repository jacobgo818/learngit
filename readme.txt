Git is a distributed version control system.
Git is free software.


$ git config --global user.name "jacob_lab"
$ git config --global user.email "jkzhang818@163.com"

git remote add origin git@github.com/jacobgo818/algorithm.git

git clone git://github.com/jacobgo818/algorithm.git

$git clone git@github.com:jacobgo818/algorithm.git


ssh-keygen -t rsa -C "jkzhang818@163.com"


git remote add origin git@github.com:jacobgo818/learngit.git
git@github.com:jacobgo818/learngit.git


GitHub�ϴ����˵Ľ�� ssh: connect to host github.com port 22: Bad file number git did not exit cleanly (exit code 128)
��.sshĿ¼���½�config�ļ���д����������
Host github.com
User jkzhang818@163.com
Hostname ssh.github.com
PreferredAuthentications publickey
IdentityFile ~/.ssh/id_rsa
Port 443