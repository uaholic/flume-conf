#flume定期采集日志配置
运行flume的shell ： ./flume-ng agent -c /home/hadoop/flume-1.8.0/conf/ -f ../conf/dir-hdfs.conf -n ag1 -Dflume.root.logger=INFO,console
