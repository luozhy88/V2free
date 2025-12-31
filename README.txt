# V2free

wget -U "Mozilla/6.0" -O ~/.config/clash/config.yaml  你的Clash订阅链接网址

## 终端运行
export http_proxy="http://127.0.0.1:7890"
export https_proxy="http://127.0.0.1:7890"
curl https://www.youtube.com
curl https://github.com

unset https_proxy
## linux 终端更改节点方法
/home/zhiyu/.config/mihomo/config.yaml #替换掉


lsof -i :7890
kill -9 <PID>

external-controller: 0.0.0.0:9090 # 如果你不是从本机访问，需要从其它机器访问这个Clash Dashboard ,则改为：0.0.0.0:9090
external-ui: /etc/clash/clash-dashboard # clash-dashboard的路径；
secret: 'luozhiyu' # PaaRwW3B1Kj9 是登录web管理界面的密码，请自行设置你自己的,不要照抄教程中的密码；


#curl google.com


# host 如果后面IP能ping通也可以，后面域名不通无所谓
 /etc/hosts
https://site.ip138.com/github.com/ #更好用
140.82.112.3 github.com
188.184.98.238 zenodo.org
13.35.41.90 huggingface.co
13.35.41.90 cdn-lfs.huggingface.co


centos:sudo systemctl restart NetworkManager
/etc/init.d/networking restart

export HF_ENDPOINT=https://hf-mirror.com
git clone https://hf-mirror.com/ds4sd/docling-models


# 网速测定
sudo apt install speedtest-cli  # Debian/Ubuntu
sudo yum install speedtest-cli  # CentOS/RHEL
speedtest-cli


