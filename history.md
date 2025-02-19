[root@oracle ~]# history
    1  hostnamectl set-hostname oracle
    2  reboot
    3  poweroff
    4  echo "TERM=xterm" >> .bashrc
    5  clear
    6  cd /tmp
    7  wget
    8  sudo update-alternatives --config 'java'
    9  sudo yum install java-17-openjdk
   10  java -version
   11  yum install curl tar
   12  useradd -r tomcat
   13  curl https://dlcdn.apache.org/tomcat/tomcat-10/v10.0.23/bin/apache-tomcat-10.0.23.tar.gz -o apache-tomcat.tar.gz
   14  ls -l
   15  ls -l apache-tomcat.tar.gz 
   16  rm apache-tomcat.tar.gz
   17  curl https://dlcdn.apache.org/tomcat/tomcat-10/v10.1.36/bin/apache-tomcat-10.1.36.tar.gz -o apache-tomcat.tar.gz
   18  ll
   19  du -sh apache-tomcat.tar.gz
   20  lsblk
   21  mkfs.xfs /dev/sdb
   22  mkdir -p /App_Data
   23  mount /dev/sdb /App_Data/
   24  df -hT
   25  cp apache-tomcat.tar.gz /App_Data/
   26  cd /App_Data/
   27  ls
   28  tar xvfz apache-tomcat.tar.gz 
   29  ls
   30  mv apache-tomcat.tar.gz /tmp
   31  ll
   32  mv apache-tomcat-10.1.36 tomcat
   33  ll
   34  chmod -R tomcat:tomcat tomcat
   35  chown -R tomcat:tomcat tomcat
   36  cd tomcat/
   37  ls
   38  cd bin/
   39  ls
   40  pwd
   41  export PATH=$PATH:/App_Data/tomcat/bin
   42  echo "export PATH=$PATH:/App_Data/tomcat/bin" >> /root/.bashrc 
   43  echo "export PATH=$PATH:/App_Data/tomcat/bin" >> /hell/.bashrc 
   44  echo "export PATH=$PATH:/App_Data/tomcat/bin" >> /home/hell/.bashrc 
   45  echo "export PATH=$PATH:/App_Data/tomcat/bin" >> /home/tomcat/.bashrc 
   46  su - tomcat
   47  nano /etc/systemd/system/
   48  nano /etc/systemd/system/tomcat.service
   49  pwd
   50  nano /etc/systemd/system/tomcat.service
   51  systemctl daemon-reload
   52  systemctl start tomcat
   53  journalctl -xe
   54  nano /etc/selinux/config
   55  reboot
   56  cd /App_Data/
   57  ls
   58  cd tomcat/
   59  ll
   60  pwd
   61  systemctl start tomcat
   62  env
   63  history
   64  export PATH=$PATH:/App_Data/tomcat/bin
   65  systemctl start tomcat
   66  journalctl -xe
   67  cd /App_Data/
   68  ll
   69  mount /dev/sdb /App_Data/
   70  systemctl start tomcat
   71  systemctl status tomcat
   72  ps aux |grep 8080
   73  ps aux 
   74  ps aux | grep tomcat
   75  netstat -tulpn
   76  curl 127.0.0.1:8080
   77  ifconfig
   78  ls
   79  ll
   80  cd ..
   81  cd /App_Data/
   82  ll
   83  cd tomcat/
   84  ls
   85  cd conf/
   86  ls
   87  nano server.xml 
   88  systemctl stop tomcat
   89  systemctl status tomcat
   90  systemctl start tomcat
   91  lsof -i -p
   92  man lsof
   93  lsof -i -n -p
   94  lsof -i -n -P
   95  lsof -i -n -P |grep LISTEN
   96  systemctl start tomcat
   97  systemctl status tomcat
   98  netstat -tulpn
   99  nano server.xml 
  100  systemctl stop tomcat
  101  systemctl start tomcat
  102  lsof -i -n -P |grep LISTEN
  103  nano server.xml 
  104  systemctl stop tomcat
  105  systemctl start tomcat
  106  lsof -i -n -P |grep LISTEN
  107  curl localhost
  108  nano server.xml 
  109  iptables -t nat -I PREROUTING -p tcp --dport 80 -j REDIRECT --to-port 8080
  110  service iptables save
  111  /sbin/service iptables save
  112  iptables -L
  113  iptables -t nat -I PREROUTING -p tcp --dport 80 -j REDIRECT --to-port 8080
  114  iptables -L
  115  ifconfig
  116  nano server.xml 
  117  systemctl stop tomcat
  118  systemctl start tomcat
  119  @lsof
  120  lsof -i -n -P |grep LISTEN
  121  nano server.xml 
  122  systemctl stop tomcat
  123  systemctl start tomcat
  124  lsof -i -n -P |grep LISTEN
  125  ifconfig
  126  iptables -t nat -A PREROUTING -i ens18 -p tcp --dport 80 -j REDIRECT --to-ports 8080
  127  iptables -L
  128  systemctl status iptables
  129  systemctl status iptables.service
  130  iptable stop
  131  systemctl status iptables.service 
  132  systemctl start iptables.service 
  133  iptables -t nat -A PREROUTING -i ens18 -p tcp --dport 80 -j REDIRECT --to-ports 8080
  134  history
  135  service iptables save
  136  service iptables start
  137  ls
  138  cd ..
  139  cd bin/
  140  ls
  141  nano startup.sh 
  142  ls
  143  cd ../conf
  144  ls
  145  nano server.xml 
  146  systemctl start tomcat
  147  systemctl status tomcat
  148  lsof -i -n -P
  149  netstat -tulpn
  150  systemctl stop tomcat
  151  systemctl start tomcat
  152  netstat -tulpn
  153  curl localhost 8080
  154  curl localhost:8080
  155  poweroff
  156  cd /App_Data/
  157  ls
  158  history
