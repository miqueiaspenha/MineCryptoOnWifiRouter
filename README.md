# MineCryptoOnWifiRouter
 
This is a small Tutorial that shows you how to mine Duco on a wifi router. Duco is a crypto that can even be mined on such low power devices.

1. Flash your router with openwrt. There many guides for your specific router out there.
2. SSH into your router. Under Linux run: "ssh root@[routerip]. Under Windows use Putty. The default port 22 is fine.
3. type: "opkg update" and then"opkg install python3" to install python.
4. Now use a program like winscp to get the Minimal_PC_Miner.py script onto your router. Theres also a different Script here.
5. Then go back to ssh and type "python3 Minimal_PC_Miner.py"
6. Thats it! Your router is now mining crypto
