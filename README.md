<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="style.css">
<head>
<body>
<h1>Nmap[Network Mapper]</h1>


<h4>Network Scanning  Techniques </h4>

+ nmap 192.168.0.1
+ nmap 192.168.1.1
+ nmap 192.168.0.0/24
+ nmap 192.168.1.0/24
+ nmap -sn 192.168.0.0/24
+ nmap -sn 192.168.1.0/24
+ nmap -sP 192.168.0.0/24
+ nmap -sP 192.168.1.0/24
+ nmap --randomize-hosts 192.168.0.0/24
+ nmap --randomize-hosts 192.168.1.0/24
+ nmap --randomize-hosts 192.168.0.0-255
+ nmap --randomize-hosts 192.168.1.0-255
+ nmap -sS -A 192.168.0.102
+ nmap -sS -A 192.168.1.102

<h4>Port Scanning Options</h4>


+ nmap -F 172.16.50.4
+ nmap -p 80 172.16.50.4
+ nmap -p http 172.16.50.4
+ nmap -p "sm*" 172.16.50.4
+ nmap -sU -sT -p U:53,T:25 172.16.50.4
+ nmap -p "*" 172.16.50.4
+ nmap --top-ports 54 172.16.50.4


<h4>Scripting Techniques</h4>

+ nmap --script banner 172.16.50.4
+ nmap --script default 172.16.50.4
+ nmap -p 21 --script-trace --script ftp-anon 172.16.50.4

<h4>Operating System detection Techniques</h4>

+ nmap -O 172.16.50.4
+ nmap -O --osscan-guess 172.16.50.4
+ nmap -sV 172.16.50.4
+ nmap -sV --version-trace 172.16.50.4
+ nmap -sR 172.16.50.4

<h4>Fast Scanning Techniques</h4>

+ nmap -v  172.16.50.4
+ nmap -vv 172.16.50.4
+ nmap -v -A 172.16.50.4
+ nmap -vv -A 172.16.50.4
+ nmap --randomize-hosts -v 172.16.50.4/24
+ nmap --script banner -v 172.16.50.4
+ nmap --script default -v 172.16.50.4
+ nmap -p 21 --script-trace --script ftp-anon -v 172.16.50.4
+ nmap -O -v 172.16.50.4
+ nmap -O --osscan-guess -v 172.16.50.4
+ nmap -sV -v 172.16.50.4
+ nmap -sV --version-trace -v 172.16.50.4
+ nmap -sR -v 172.16.50.4
+ nmap -p 80 -v 172.16.50.4
+ nmap -p http -v 172.16.50.4
+ nmap -p "sm*" -v 172.16.50.4
+ nmap -sU -sT -v -p U:53,T:25 172.16.50.4
+ nmap -v -p "*" 172.16.50.4
+ nmap --top-ports -v 54 172.16.50.4
+ nmap -sS -v 172.16.50.4
+ nmap -sT -v 172.16.50.4
+ nmap -sX -v 172.16.50.4
+ nmap --scanflags ACKPSH -v 172.16.50.4
+ nmap -sO -v 172.16.50.4
+ nmap --send-eth -v 172.16.50.4
+ nmap -sn -v 192.168.0.0/24
+ nmap -sn -v 192.168.1.0/24
+ nmap -sP -v 192.168.0.0/24
+ nmap -sP -v 192.168.1.0/24
+ nmap --data-length -v 172.16.50.4
+ nmap -D -v RND:172.16.50.4
+ nmap --mtu -v 8 172.16.50.4
+ nmap badsum -v 172.16.50.4
+ nmap -oG - 192.168.1.0-255  -vv


<h4>Advanced Scanning Techniques</h4>

+ nmap -sS 172.16.50.4
+ nmap -sT 172.16.50.4
+ nmap -sX 172.16.50.4
+ nmap --scanflags ACKPSH 172.16.50.4
+ nmap -sO 172.16.50.4
+ nmap --send-eth 172.16.50.4

</body>
</html>






