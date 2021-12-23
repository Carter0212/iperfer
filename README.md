# iperfer
NTUST network computer homework1 iperfer is a common tool used to measure network bandwidth. You will write your own version of this tool using sockets. You will then use your tools to measure the performance of certain networks. Your tool, called Iperfer, will send and receive TCP packets between a pair of hosts using sockets.

操作手冊
Step 1
依照作業提示執行程式碼(先執行Server再執行Client，如果沒有先)
使用本地地址當範例
Ex: server:python ./iperifer.py -s -p 2277
    client:python ./iperfer.py -c -h 127.0.0.1 -p 2277 -t 10
Step 2
等待時間(取決於你輸入的秒數)
Step 3
查看輸出結果



參考資料
https://clay-atlas.com/blog/2019/10/15/python-chinese-tutorial-socket-tcp-ip/
https://docs.python.org/zh-tw/3/library/socket.html?highlight=socket#module-socket
https://docs.python.org/zh-tw/3/library/time.html?highlight=time#module-time
https://docs.python.org/zh-tw/3/library/sys.html?highlight=sys#module-sys
