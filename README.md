# Switch-to-Switch-in-Cisco-Packet-Tracer

## Objective 

Two switches connected are all about expansion and distance. Imagine a very long hallway, and within those hallways, you have 50 rooms, which are the computers, and you only have one small connection box, which is a switch that holds up to 24 plugins for those devices. You cannot fit everyone within one box. What you can do is have a long cable connecting two different switches for those 50 rooms.

When I connect these two switches, I use a crossover cable. Think of it like a phone call for a conversation to work my mouth. The sender has to connect to your ear, which is the receiver. If we connect mouth to mouth, nobody hears anything. A crossover cable internally crosses those wires so the two switches can hear each other.

# Steps Taken

1. Building on my last project, I decided to scale things up. I set up two switches and six computers to simulate a larger office. I split them up by connecting three PCs to 1 switch and three to the second. Think of it like having two different power strips in one big room. If you have too many gadgets to plug into one strip, you're going to get a second strip. By looking at the physical layer, which includes the actual plugs and cables, I made sure that the handshake between the two switches was solid, so all six computers could talk to each other like one big happy family.

In the images below, you can see that the computers are within the main IT closet from a physical view.

<img width="590" height="346" alt="image" src="https://github.com/user-attachments/assets/d41de5f8-0de1-4fa3-90ac-13b636e69945" />

For now, you can only see three computers plugged into one switch, while the second switch has nothing plugged into.

<img width="648" height="524" alt="image" src="https://github.com/user-attachments/assets/2cca2ee2-9ffe-49d8-b4e6-34e2f42103b6" />


2. Within the physical layer, I created a new closet for it, and we're going to be separating these closets with the switches and the PCs that we previously created.

<img width="1312" height="660" alt="image" src="https://github.com/user-attachments/assets/f8f62e4b-ecf9-4b4b-a8ad-fa617aec5c90" />

3. I open the window to start moving the physical devices, such as the PCs and the switches, to the new closet.

<img width="764" height="588" alt="image" src="https://github.com/user-attachments/assets/5dd79250-5d97-4e6d-bd22-a3ee650ba7d5" />

The new closet now has the switch and the three computers.

<img width="798" height="738" alt="image" src="https://github.com/user-attachments/assets/83b8d963-f6ae-463d-a87e-76672bfe1680" />


4. I've connected the computers to the switch. Now I will be using Copper Cross cables to connect the switches.

While modern switches often use Auto MDI-x to allow standard straight-through cables for this purpose, crossover cables ensure connectivity between older or non-auto-sensing devices. 

I clicked on the copper cross cable and connected Switch 2 to Switch 1.

Currently, it is red/orange because it needs time to connect. 
<img width="998" height="484" alt="image" src="https://github.com/user-attachments/assets/c1ab2c4f-e077-4fa7-b75e-2644a0112322" />

5. I will now configure PC3 and give it a Static IP Address.
I will give it an IPv4 Address of: 192.168.1.20


<img width="1172" height="818" alt="image" src="https://github.com/user-attachments/assets/48e97a20-72d6-44ab-a250-6044100d1011" />


6. I will do the same for PC5, which is connected to the same switch.
I will give it an IPv4 Address of: 192.168.1.21

<img width="1210" height="794" alt="image" src="https://github.com/user-attachments/assets/ba95a21a-e00c-4157-82a0-5d9961242cf6" />

7. Following the same steps, I will do the same for PC0.
I will give it an IPv4 Address of: 192.168.1.10

<img width="1226" height="752" alt="image" src="https://github.com/user-attachments/assets/0dd66d9e-c8ba-41e6-ba0b-ec34665e88fa" />


8. From PC5, I will ping PC0 with the command "ping 192.168.1.10."

<img width="1424" height="618" alt="image" src="https://github.com/user-attachments/assets/d047f201-bee0-41a1-bcfb-0b1d562dbe44" />

9. I will now simulate it. We can see the envelope from PC5 go to the Switch2 to Switch1 and then look for PC0, then back to Switch1 to Switch2 and back to PC5. Letting PS5 know that PC0 hears you and is here.

<img width="1086" height="562" alt="image" src="https://github.com/user-attachments/assets/535ea890-7a71-43cc-b883-bf4c4f661a96" />

<img width="1254" height="614" alt="image" src="https://github.com/user-attachments/assets/8bade33a-dd8b-4ab5-ade6-c64c76de73ad" />

<img width="1114" height="450" alt="image" src="https://github.com/user-attachments/assets/35404ab8-c8d1-4310-aa68-125267d45148" />

<img width="1072" height="470" alt="image" src="https://github.com/user-attachments/assets/f350cdc6-08ce-4206-9b43-f05e71156ee8" />

Now back.

<img width="1068" height="508" alt="image" src="https://github.com/user-attachments/assets/4efbac0a-360b-4e03-94c9-2d5d6646736a" />


<img width="1338" height="594" alt="image" src="https://github.com/user-attachments/assets/b00c0a24-27f6-451a-b357-22e82270c32c" />


<img width="964" height="476" alt="image" src="https://github.com/user-attachments/assets/5f9f32ee-ba58-497f-9968-3acfcdac0237" />

<img width="320" height="386" alt="image" src="https://github.com/user-attachments/assets/3745442a-9ef6-4e64-97a3-92772e23f760" />

