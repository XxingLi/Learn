1.

	mkdir -p lx_ws/src
	cd src
	catkin_init_workspace
		输出Creat symlink“/home/glm/lx_ws/src/CMakeLists.txt” pointing to "/opt/ros/indigo/share/catkin/cmake/toplevel.cmake"
	
2.

	$ cd ~/catkin_ws/
	$ catkin_make

3.

	$ source devel/setup.bash





开机启动roscore
	
	1、编写script.sh的脚本，内容为：
		#！ /bin/bash
		source /opt/ros/hydro/setup.sh
		roscore
	2、Startup Applications 中添加
		那么随便写
		command为gnome-terminal -x /home/nick/script.sh
									script.sh的路经
	


#有线连接开发板，无线上网的设置
	有线网关设置为0.0.0.0并且跟无线不在同一个网段
	比如无线在1网段，有限在2网段即可