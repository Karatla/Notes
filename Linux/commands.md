cd      cd../      cd -
ls   ls-l
chmod
pwd
rm   rm -rf
mkdivim
mkdir
ps aux
pgrep
kill
su 
sudo passwd
netstat -ntl   netstat -ano
ctrl c   ctrl z   fg  bg
jobs
history
find
reptyr  screen -ls  screen -r   screen -d   screen -S
scp -i [] user@ip:file file
cat file>>file

服务启动service .. start

systemctl start docker 后台启动命令
systemctl enable docker 开机启动

sudo bash
sudo passwd toot

source ~/.bash_profile

（1）复制 a.txt 到 test 目录下，保持原文件时间，如果原文件存在提示是否覆盖。
cp -ai a.txt test



（1）将文件 test.log 重命名为 test1.txt
mv test.log test1.txt
（2）将文件 log1.txt,log2.txt,log3.txt 移动到根的 test3 目录中
mv llog1.txt log2.txt log3.txt /test3
（3）将文件 file1 改名为 file2，如果 file2 已经存在，则询问是否覆盖
mv -i log1.txt log2.txt

source $HOME/.cargo/bin

chmod 权限

brew services

apt-get update
apt-get install
apt-get search

yum -y install screen

DOCKER:
docker run -it -d -p 127.0.0.1:5000:3306 mysql /bin/bash

docker run --name root -e MYSQL_ROOT_PASSWORD=MSj316492696 -it -d -p 127.0.0.1:5000:3306 mysql /bin/bash

docker exec -it d9d6240dffe1 /bin/bash
exit

docker exec -It d9d6240dffe mysql -uroot -pMSj3164926 -e 'show database'

#ping check
/proc/sys/net/ipv4/icmp_echo_ignore_all

sudo lsof -i -P -n | grep LISTEN
