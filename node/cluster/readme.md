- WEB 跟桌面(单机)最大区别？
  
  localhost:1234  n个人可以请求  上限？
  并发请求 
  分配给每个用户一个线程， fs 读取一个文件 index.html
  I/O 吃紧 300左右并发请求 物理
  ？ 解决？
  ngnix （负载均衡） 那些机器空闲 ， 把用户送到这台机器的IP地址 钱？
  如何充分发挥每台机器的性能？ 多核，
  1234 =》 node进程， =》 一个进程， =》 CPU
  把CPU都用上，