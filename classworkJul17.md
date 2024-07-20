# Part 1 - Research Paper Exploration

**URL:** https://ieeexplore.ieee.org/document/8718630

<p>SUMMARY: The research paper, “A Survey of Computer Architecture Simulation Techniques and Tools”, is an analysis created by Ayaz Akram and Lina Sawalha of visual simulators for computer processor models. The paper was created as a way to assist those researching computer architecture to select a simulator to use during their research, since there is a clear lack of proper documentation in the world pertaining to this subject, and contains several tables and models to further elaborate upon their information. The introduction goes on to explain the main goal of a simulation, as well as explaining the role of the survey itself and what it covers.</p>

<p>The survey then elaborates on how they went about organizing the simulators. Some of the methods they used include organizing based on the detail of the simulation (gauging how each simulator implements varying mixtures of functionality and speed), organizing based on target scope (either activating the full operating system or just specific applications), and organizing based on the input into the simulator itself (either being trace-driven or execution-driven).</p>

<p>The article reflects on the evaluation of the simulators, and lists the six metrics they use to evaluate them: accuracy (how accurate the simulator is to the real hardware), performance (how fast or slow the simulator runs while active), level of details (how many details the simulator includes), easiness of development, flexibility (how flexible the simulator is to modify or configure), and user friendliness (how easy it is for outside users to learn). The survey then gives a summary of existing simulators in an easy-to-access table.</p>

https://ieeexplore.ieee.org/mediastore/IEEE/content/media/6287639/8600701/8718630/sawal.t3-2917698-small.gif

<p>The survey then discusses the challenges in simulation, and offers some suggestions on how to rectify them. They also discuss simulator validation, the process of confirming that a simulator accurately represents a piece of hardware. Finally, they compare six different timing simulators, discuss the methodology adopted to compare the results of these simulators with their real hardware, and display the research they acquired going through the simulators and their errors.</p>

<p>As the survey concludes, it reflects on their previous examination, discusses that there is a greater need for better simulation techniques due to the advancement of multicore architecture, and reflects on simulation validation.</p>

**ANALYSIS:** <p>As highlighted in the survey, simulators are designed to demonstrate new ideas for parts of a computer system. They are also made to help computer architects evaluate and understand how existing systems behave and operate, and can be a useful tool in debugging these systems.</p>

<p>There are two main categories of challenges that simulations can face, both relating in some way to their performance or accuracy. The first is Slow Simulation, an issue that has become more and more prevalent due to simulating multicore processors.</p>

**APPLICATION:** <p>Knowing what I know now about simulators and how they function, I might be able to better understand the simulators that have been and may eventually be provided to me throughout this course.</p>

# Part 2 - Evaluating emulsiV
<p>According to Guillaume Savaton of ESEO, emulsiV is a visual simulator created to run an RISC (reduced instruction set computer) processor called Virgule. The program itself is a very basic, “minimal” (as they describe themselves) program that only accepts the instructions that a compiler would generate from a stand-alone program of its type. This means that anyone thinking of using the program will be capable of visualizing basic examples of processor instructions, but will have to search elsewhere for more complex demonstrations. It was designed with the specific purpose of teaching computer architecture to beginners in their personal program.</p>

<p>The simulator comes pre-packaged with several pre-loaded examples, including writing the word “hello”, sending an echo to the computer, and performing a basic input and output loop. The program even designates which step is active with an “animation” toggle, and can be sped up or slowed down to a user’s convenience.</p>
