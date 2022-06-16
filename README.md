# MikroTik Repo
## Firewall
1. BogonIP network list
   - `/tool fetch url="https://raw.githubusercontent.com/RaynoP/MikroTik/main/bogons.rsc"`
   - `/import bogons.rsc`
2. 

## Routing

## Scripting
### Pulling and running from Git in ROS
```
/tool fetch url="<GitRepo>/ScriptName.rsc"
/import ScriptName.rsc
```

## VPNs
### WireGuard in ROS 7.3.1
Config is simple as per internet sheets. But there is one caveat: You HAVE to set the `persistant keepalive` to a value. Else the tunnels do NOT establish.
Sample config had both ends behind internet accessable NATs on ROS 7.3.1 on a CCR1009 and a DL140 server running ROS x86


## Git README Cheatsheet
https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
