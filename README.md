python macchanger
terminal code:

ifconfig eth0 down

ifconfig eth0 hw ether 00:11:22:33:44:55

ifconfig eth0 up


 
 pycharm code:
 
import subprocess

print("MyMACChanger started")

subprocess.call(["ifconfig","eth0","down"])
subprocess.call(["ifconfig","eth0","hw","ether","00:11:22:33:44:44"])
subprocess.call(["ifconfig","eth0","up"])
