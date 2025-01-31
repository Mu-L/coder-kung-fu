
## CPU相关实验
- [likely 和 unlikely 汇编结果对比](tests/cpu/test01)
- [read 系统调用开销](tests/cpu/test02)
- [read 进程上下文切换开销](tests/cpu/test03)
- [read 协程上下文切换开销](tests/cpu/test04)
- [read 线程上下文切换开销](tests/cpu/test05)

## 磁盘相关实验
- [使用fio磁盘压测工具进行性能压测分析](tests/disk/test01)

## 内存相关实验
- [内存访问延时测试](tests/memory/test01)
- [内存访问带宽测试](tests/memory/test02)

## 网络相关实验
- [PHP单语言的百万连接测试源码](tests/network/test01)
- [通过多 IP 达成单机百万连接（支持c、java、php三种语言）](tests/network/test02)
- [通过端口重用达成单机百万连接（支持c、java、php三种语言）](tests/network/test03)
- [一个模拟 tcpdump 的简单抓包程序](tests/network/test04)
- [简单的veth通信](tests/network/test09)
- [用 bridge 连接本机上的多组 veth，使其可以互相通信](tests/network/test05)
- [命令行使用 namespace 的简单实验](tests/network/test06)
- [手工模拟实现一个可以和外部通信的容器网络](tests/network/test07)
- [socket端口复用SO_REUSEPORT测试](tests/network/test08)

## eBPF 程序
- [使用 libbpf 开发的 hello world eBPF 程序](tests/ebpf/test01)