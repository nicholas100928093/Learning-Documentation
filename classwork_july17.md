Part 1 : Research Paper Exploration

Reference : https://ieeexplore.ieee.org/document/8718630

Summary : 
	In this study, the authors find that simulators people studying in the computer architecture areas are using, play important roles towards the improvement of computer architecture research. 
The main goal of using these simulators is to help design and model new ideas for creating newer and better parts for a computer (microprocessor, memory, peripherals). The computer architects
can also use the simulators to test and evaluate the newly designed computer parts or already existing systems and study the results, like the performance of the newly designed parts and the 
amount of power it consumes. The authors of this paper also find that these simulators can be classified into different groups based on three important factors : the detail of the simulation, 
the scope of the computer system being simulated (also called the target) and the inputs to the simulator. They also find that one simulator does not necessarily only belong to one of the categories, 
instead it can belong to multiple at the same time. Some of these simulators can simulate entire operating systems and run benchmarks as they would normally run on a real computer using that operating
system, or some simulators could run only certain applications at a time instead of the entire operating system. The simulators could also be given pre-set instructions to be run or only use binaries 
and benchmark executables. The authors also followed certain methodologies to accurately conduct their experiments. This includes trying to match the simulators being experimented with a target system, 
being Intel’s Haswell microarchitecture (core i7-4770). They also compared workloads and the performance on real hardware with the SPEC-CPI2006 and a subset of MiBench benchmarks. Even though the
execution times can take a long time, the authors had to warm up the hardware with a warm up period and run test instructions, then ran the benchmark multiple times to accurately find a result. 
Another important finding from the paper, was that the simulators need to be validated so that they do not include errors, such as modeling, specifications or abstraction errors.

Critical Analysis : 
3 majors advantages of computing applications as presented in the paper
	The first advantage for the application of simulators for computing is that it allows the researchers in this field to create and design new parts of a computer system. This can include
microprocessors, memory and even peripherals. The researchers can use the simulations to test those parts and determine if there needs to be any improvements towards their performance or how 
limit the amount of power the parts consume at a time while in use. 
	The second advantage would be that the simulators can help people researching computer architectures because they can simulate existing systems. This allows the researchers to better understand
the behavior and how existing systems work. By doing so, they can first encounter bugs in the simulator, and when this same bug appears in a real existing system, the researchers can easily apply and
test the solution they may have developed with the simulator.
	The third advantage would be being able to validate the simulators. Validating simulators mean the process in which the simulator can accurately simulate the desired hardware or device. This step
of validation is important because then researchers can determine if there are any errors within the simulator, like modeling, specification or abstraction errors. Validating simulators allows
comparisons between real life hardware and the simulated hardware, and also allows for experimentation on both.

2 potential limitations highlighted by the authors
	The first limitation that was highlighted by the authors was the time it takes for a simulation to complete. The researchers want the simulations to produce an accurate time that it takes to
complete certain tasks and instructions, which could take from an hour to several days. The main reason that the simulation could take long periods of time to complete are the complexity of the
microarchitectures and the length of programs created in the present because they contain a large amount of instructions. Some solutions the authors have developed are sampled simulations (only
simulating small parts of the benchmark, instead of the entire thing), statistical simulations (combines detailed and analytical simulations, they are also small in size so that they can be processed
at faster speeds), parallelizing simulations (uses checkpoints in sampled simulations, then they can run simulations from those checkpoints at the same time as other simulations) or by using a Field
Programmable Gate Array (FPGA) (the simulators can use parallelism from the FPGAs to attain higher simulation speeds.
	The second limitation highlighted by the authors is the accuracy of the simulations because design choices are based on the result of the simulations. The first step for the developers is to 
ensure that the simulator is functioning correctly and achieving the target they want the simulation to achieve. Secondly, the simulation's result should determine how the device would work if it
was real. Three main errors that are usually found, according to the study, are modeling errors, specification errors and abstraction errors. First, modeling errors are when the desired function
is not working or modeled properly in the simulator, and a solution to reduce these errors is by designing and testing the structures more carefully. Secondly, specification errors are when there
is not enough known about how the simulation is intended to work. The solution can only be achieved when there is a clear understanding of the goal of the simulation and what it would look like
in real life. Lastly, abstraction errors are when the developers try to trade off certain aspects of the simulation for others, like better speed but less detail, and there are less of these errors
because technology continues to improve in the present, meaning faster processing and simulation times.

Application : 
	The methodology of having a target system to match is a good place to start when researching other simulators. This can apply to our course activities because if we ever need to use the
simulators to compare to other simulators, having a solid base and starting point that is the same for each of the simulators, we can get more consistent results when testing them. The next
methodology of testing with currently existing hardware can apply to our course work because if we were to try and design a new hardware piece, we can try it on the existing systems and see
what can be improved on. Then, we can try to create a simulation idea to simulate the existing system but with minor modifications to improve on the flaws found earlier. Lastly, validation of
simulators, as found in the paper, is useful for anytime we are trying to create new hardware or even software. This can apply to our coursework because through the steps of development, we can
reassure ourselves with lower chances of errors, whether it be in simulations or when testing on real current existing systems


Part 2 : Evaluating emulsiV

Reference : https://eseo-tech.github.io/emulsiV/

Overview : 
	emulsiV is a visual simulator of a RISC processor called Virgule. Virgule is a 32-bit RISC processor core that will use a minimal subset of instructions from the RISC-V instruction set.
Defined by the website, minimal in this case meant that the processor will only accept instructions that a C compiler would generate from a C program. emulsiV is also a tool that can be used
for teaching computer architecture and digital design to beginners. 

Advantages and Disadvantages : 
3 advantages of using emulsiV for visualization and simulation purposes
	The first advantage of emulsiV is that it is an open architecture that can be used and implemented without permissions. The developers nor the users of emulsiV need to consistently ask for
permissions to use the simulator, which allows anyone to use it at any time. The second advantage of emulsiV is that it is built with a simple instruction set, but can still be used as a target
for a C compiler. The third advantage of emulsiV is that the architecture of the simulator is similar to existing systems and simulators, which are also being used in the industry.

2 disadvantages or limitations of using emulsiV
	The first limitation for emulsiV is that only certain instruction sets were built into the website simulator from the developers. But the simulator itself is still usable with simpler 
instruction sets, even though there aren’t the most options. The second limitation is that emusliV can only accept instructions that a C compiler would generate from a pure C program, meaning 
that if any instructions that a C compiler could not generate, the website simulator might not be able to simulate it.

Comparison with Traditional Tools : 
	Comparing emulsiV with CPU Visual Simulator, another website simulator that was demonstrated and studied in the course. CPU Visual Simulator is very organized and there are less numbers
to overload the user when they look around the display, but emulsiV is a bit more detailed with the multiple numbers and displays for addresses. This simulator also gives detailed steps and
worded out descriptions of what is happening within the simulator. This makes it easier to follow in my opinion because of not only the worded out descriptions of the steps but also the animations.
emulsiV on the other hand is similar in this way with the animations. Their performance is both pretty stable as the simulators and websites don't struggle to run the simulation. Both simulators are
also very easy to use and navigate, and come with a description of the goals and specifications of the website and simulator itself. They also both come with examples that can be used and are easily
modifiable to suit the users’ needs and can be saved for later use. 

Practical Application : 
	I think that a project that involves emulsiV, and also uses instruction sets that follow the guidelines of the simulator, is where emusliV will be used very effectively. 
This project could give good outcomes because it follows the guidelines and suits how the simulator should be used. A research scenario that could be very effective for emulsiV is
if we were to test the absolute limit of the simulator. If we can find to what extent different instruction sets can or cannot be used by the simulator, then future developers and
users of the simulator can have a better idea and have a set list of instruction sets that will or will not work. Meaning, if there was an instruction set name that a user wants to test,
they can check the list and immediately know if it will work or not. 

