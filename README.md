# TheLastStand

环境配置：
sudo apt-get install mininet python3-ryu

运行方式:
ryu-manager --observe-links shortest_paths.py
这里使用的是python3

打开一个新的窗口
sudo python run_mininet.py single 3
这里使用的是python2，因为mininet本身配置的是python2，python3会有倒入的问题

运行开始之后，等待第一个窗口配置结束
pingall测试网络连通性

结束之后，运行sudo mn -c删除mininet占用
