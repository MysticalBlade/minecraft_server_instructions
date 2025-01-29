# Minecraft Server Instructions(short ver)

# 1. Needed files
We need the server files(latest download here https://www.minecraft.net/en-us/download/server) and Radmin VPN, to not require port forwarding

# 2. Building the server
First, locate the place where you put the server file. This should be in a seperate folder anyways. Open the jar file, this should generate some folders. Go into EULA.txt and change to TRUE, this accepts their EULA agreement. Then go into command line(cmd or powershell) and run the java file with the command "java -Xmx1024M -Xms1024M -jar *serverfilename*.jar" java -jar is running the file, -Xmx1024M and -Xms1024M is allocating memory to the server. You should see a little window pop up showing that you have

# Note: BE SURE YOU HAVE THE CORRECT JAVA VERSION ON YOUR MACHINE, FOR 1.21.4 ITS JAVA 21, FOR OTHER VERSIONS IT DIFFERS, WE ARE RUNNING 1.21.4 SO HAVE JAVA 21

# 3. Setup Radmin VPN
https://www.radmin-vpn.com/ In all honestly, you just need to run it and follow its instruction. This keeps you from having to do port forwarding, not like we can do it in USFs eduroam anyways. Should explain why port forwarding is potentially dangerous for the uninitiated. 

# 4. Connect to your minecraft server
Go into minecraft(correct version), and then connect to the server via radmin vpns ip and the server port(something like 111.111.1.1:11111). Its IP:PORT, you can change the port number in the properties, the default port is 25565, you should change it to prevent griefing but for demonstration just keep it at 25565


# ISSUES
1. Whitelisting
2. Mismatched java version
3. Pirated minecraft

Read on these, read on port forwarding and try to do make a server yourself
