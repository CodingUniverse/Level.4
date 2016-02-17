# Level.4
An app for protecting your iOS network traffic

Level.4 works on iOS 9+, you can use it to protect your network traffic.

LightSword is a server program written by Node.js. And to use Level.4, you should install LightSword on your server. It's very simple! 

1.Install Node.js 4.0+ from https://nodejs.org

2.Install LightSword by npm

```
> npm i -g lightsword
```

3.Run LightSword 

```
> lsserver --port 8081 --password mypassword --fork --cluster
```

OK, your server is running. To get more information, type: 'lsserver -h' in your terminal.

Now, run Level.4 on your iOS device, tap 'Add Server Configuration', input your server label, address, port number, password, and save it. Switch on the connection toggle, Level.4 is going to protect your network traffic.

Roadmap:

~~1.Debug TCP/IPv4 stack~~

2.Bypass China IP

3.Compatible with SS

4.IPv6

Privacy Policy
---

Level.4 dosen't collect any data about the user.

Progress
---

~~0.1.0 Not Stable (Rejected)~~

~~0.2.0 IMPORTANT UPDATE: Lots of bugs are fixed (Ready for Sale)~~

***0.2.3 IMPORANT UPDATE: Improved performance (Waiting For Test)***

0.3.0 Bypassing China IP (Developing)
