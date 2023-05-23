### 相关说明及注意点请查看[warp系列视频说明](https://www.youtube.com/playlist?list=PLMgly2AulGG-WqPXPkHlqWVSfQ3XjHNw8) [更新日志](https://ygkkk.blogspot.com/2022/09/cfwarp-script.html)

### 一、WARP多功能VPS一键脚本，支持纯IPV4、纯IPV6的VPS直接安装，主流linux系统均支持
```
bash <(wget -qO- https://gitlab.com/rwkgyg/CFwarp/raw/main/CFwarp.sh 2> /dev/null)
```
或者
```
bash <(curl -Ls https://gitlab.com/rwkgyg/CFwarp/raw/main/CFwarp.sh)
```

#### 1、强制终止warp-go：```kill -15 $(pgrep warp-go) ```

#### 2、终止wgcf：```systemctl stop wg-quick@wgcf```


---------------------------------------------------------------------

### 二、多平台优选WARP对端IP + 无限生成WARP-Wireguard配置三合一 脚本
```
curl -sSL https://gitlab.com/rwkgyg/CFwarp/raw/main/point/endip.sh -o endip.sh && chmod +x endip.sh && ./endip.sh
```
--------------------------------------------------------------
### 三、Windows平台warp官方客户端优选对端IP应用程序

使用方法：解压下载的（WIN端warp自选IP(手动+自动).zip）文件，参考使用方法及视频教程

-----------------------------------------------------------
### WARP多功能VPS一键脚本界面图
![98ae45b09a62a30f4281bdae8586c6d](https://user-images.githubusercontent.com/121604513/230701599-1701d8a4-367c-41ab-bdae-ed05cf5100d1.png)
--------------------------------------------------------------
#### 以上脚本源码备份[Gitlab地址](https://gitlab.com/rwkgyg/CFwarp)
#### 感谢WGCF源项目代码地址：https://github.com/ViRb3/wgcf
#### 感谢CoiaPrant，WARP-GO源项目代码地址：https://gitlab.com/ProjectWARP/warp-go
#### 相关功能参考来源： [P3terx](https://github.com/P3TERX/warp.sh)、[fscarmen](https://github.com/fscarmen/warp)、[热心的CF网友](https://github.com/badafans)提供的warp endpoint优选IP脚本及注册程序

