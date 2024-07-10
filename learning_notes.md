# Learning-Documentation
Title : CPU Visual Simulator

URL : https://cpuvisualsimulator.github.io/ 

Summary : This website allows you to visualize how the parts in a CPU communicate with each other and the RAM to complete a set of instructions from code

Key takeaways
- The Program Counter always starts at 0 and is always increased by 2 every time
- At the beginning of the cycle after the Program Counter increases by 2, the first few steps are usually always : 
	- Program Counter sends information through Address Bus
	- Fetch operation is sent from Control Unit through Control Bus
	- Instruction loaded into Instruction Register
	- Opcode is decoded in the Decoder
- The address numbers are all even numbers	
	- Start from 0 and increased by 2, up to 34
	- Each address in the RAM has a different instruction

Personal insights 
- The website is very good at demonstrating the way a CPU works visually, while also giving instructions for every step	
	- Tells you what is happening and where information is being sent across the CPU

Feedback : This website has helped me understand more about the mini processes that are happening quickly in the CPU in devices I use daily

Reflection : Being able to see what happens in the CPU visually with instructions to follow demonstrates how there are many complicated processes, 
information and instructions are being sent in such a short time and small parts in a CPU. It also demonstrates how every part in a computer or devices in general
need to work and communicate together in order to perform efficiently
