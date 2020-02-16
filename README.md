# UUSSR
UUSSR-科学上网

## 安装说明
mkdir v2ray-agent  &&  \
cd v2ray-agent && \
curl https://raw.githubusercontent.com/NGKSSR/uussr/master/v2ray.sh -o v2ray.sh && \
chmod +x v2ray.sh && \
bash v2ray.sh

执行以上一键安装脚本即可!
填写信息。。等待
完成!

### 可选安装BBR

#### 支持系统：CentOS 6+、Debian 8+、Ubuntu 14+。

注意：该脚本在Vultr各个系统均测试通过，如果期间有出现任何问题，可向原作者反映帮助改善。

运行以下命令：

##### wget -N --no-check-certificate "https://raw.githubusercontent.com/chiakge/Linux-NetSpeed/master/tcp.sh" && chmod +x tcp.sh && ./tcp.sh

执行完以上命令后若出现
#### -bash: wget: command not found
请执行以下命令(执行完此命令后重新执行上面安装命令即可):
#### yum -y install wget

### Ubuntu 18.04 魔改 BBR 暂时有点问题，可使用以下命令安装：

##### wget -N --no-check-certificate "https://raw.githubusercontent.com/chiakge/Linux-NetSpeed/master/tcp.sh" apt install make gcc -y sed -i 's#/usr/bin/gcc-4.9#/usr/bin/gcc#g' '/root/tcp.sh' chmod +x tcp.sh && ./tcp.sh
