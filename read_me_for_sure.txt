Steps :

1. Turn off both public and private firewall in your target device :
    >Control Panel\System and Security\Windows Defender Firewall\Customize Settings

OR 
run the off.bat file i've added in this repo


2. from sender device (attacker)  , use the command 
> echo "hello" | nc <target ip> 5000  (hello is message)

IF YOU ARE GETTING "nc not found" ERROR, install netcat using this command
> sudo apt install netcat-openbsd

3.success , you will now get the message in your target device from attacker device
