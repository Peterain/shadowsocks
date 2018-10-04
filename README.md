System Required: CentOS7
cd /root
yum -y install python-setuptools
easy_install pip
git clone -b manyuser https://github.com/glzjin/shadowsocks.git
cd shadowsocks
pip install -r requirements.txt
cp apiconfig.py userapiconfig.py
cp config.json user-config.json
