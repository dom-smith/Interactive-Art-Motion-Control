# Interactive Art Motion Control
 
The following is an interactive art piece using your mobile device as a motion controller built in Unreal Engine 5 using Protokol and ZIG SIM

Instructions:

- First, you'll need to download the ZIG SIM app on your mobile device from either the IOS App Store or Google Play Store
- Next, ensure that both your mobile device and your Computer UE5 Project from are on the same network (I recommend using a hotspot here)
- On your mobile device, go to your Network Settings and copy the IPv4 Router address
- Paste the Router Address in both your ZIG SIM app under Settings along with the UE5 project in the BP_OSC Blueprint
- Set a custom port number in the ZIG SIM App and copy it in the UE5 project in the BP_OSC Blueprint 
- In ZIG SIM, change 'Message Format' to OSC and 'Resfresh Rate' to 30
  
- Next download Protokol on your computer here: https://hexler.net/protokol (This is how we'll recieve OSC messages from ZIG SIM)
- Open Protokol and navigate to the 'OSC' page
- Copy the port number you entered from ZIG SIM
- On ZIG SIM, on the Sensor tab, deselect everything except for Accel


  You're all set! Click Start in the ZIG SIM App and Run the UE5 Project and you'll see you're sending OSC messages to Protokol along with interacting with the UE5 Art!


 *If you're running into issues with sending OSC messages from ZIG SIM to Protokol, make sure your firewall isn't blocking these incoming messages*
