official website：https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit

Copyright © 2021 NVIDIA Corporation

# 新手如何配置JETSON NANO
一、系统部分 	

1、下载官网NANO的系统镜像：https://developer.nvidia.com/jetson-nano-sd-card-image 	

2、使用Etcher软件工具将下载的镜像烧录至SD卡中，建议SD容量为64G及以上 	

3、完成SD烧录后，将SD插入Jetson Nano，接入5V4A电源启动，按照提示完成系统信息注册 	


二、软件部分 	

1、镜像源修改：如需要换其它源，可修改/etc/apt目录下的source.list，修改源之前建议先做一个备份：mv source.list sources.list.backup 	

   更新源：切换到root权限，依次输入apt-get update,apt-get upgrade 进行更新 	
   
	
2、深度学习软件环境配置	

