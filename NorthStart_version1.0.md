# Toastboard: An Intuitive Modular Electrical Engineering Kit
## Nathan Oh

# What is Toastboard?
“What if learning electrical engineering was as easy as connecting pieces, and as intuitive as building legos?”

# What is the issue with current electrical engineering education?
Growing up in a relatively low-middle-class immigrant household, I didn’t have many opportunities as a child to deeply connect and learn about engineering. Small, university-run classes taught me the basics, while deeper knowledge in CAD, programming, and Arduino engineering was acquired solely through self-taught methods such as books and the internet. Although I am truly blessed to have become truly engrossed in the little opportunity I had, what about other children? They may not live anywhere near these basic classes, not have clear access to the internet, lack the funding for materials, etc. and may never realize the passion they might have had. Many current electrical engineering education systems prioritize profit and entertainment rather than fostering the education of children. Having experienced these systems firsthand through years of self-teaching, I believe that electrical engineering can be taught in a much more inclusive and beginner-friendly manner.
# What’s wrong with a regular Arduino and breadboard?
Of course, the best way to learn Arduino is by using an Arduino itself. So why replace it? Some of the main advantages of an Arduino, and similar microcontrollers, are the cost-effectiveness, room for innovation and expansion, encouragement of engineering thinking, and low cost. However, there are also some major disadvantages in terms of learning the system, especially for younger students or self-taught beginners, such as:
Difficult debugging
Through the process of learning, it is inevitable that a beginner will make a mistake when creating an Arduino project. Hardware errors are especially hard for beginners to detect, as electricity and breadboards do not provide specific information on mistakes, leaving novices confused on whether the issue is a programming issue, a faulty cable, a wrong pin selected, or faulty driver when the issue is, in reality, a backwards LED. The debugging system often assumes that the user has default knowledge on software or hardware concepts, and a user without this knowledge may find it incredibly difficult to fix these errors without feedback.
Little visual and intuitive feedback
With beginner programming systems like Scratch, beginners and children can often write simple programs within minutes of using the software. This is because Scratch is incredibly visually, intuitively allowing for users to understand and control what happens in their creations effectively. However, both the hardware and software aspects of Arduino are often difficult to intuitively understand. For learners without teachers to give consistent and balanced feedback, it is often difficult to understand what happens inside an Arduino and breadboard. One could argue that recently, AI has been growing as a tool for personal learning, yet it is extremely easy 
Difficulty of Arduino programming
Arduino, by default, uses essentially the C++ language, which has syntax and concepts difficult for even the average individual. Without structured repetition and teaching, learning Arduino programming may seem like an impossible task for a child with no prior engineering experience. The challenge is that Arduino often requires learning concepts first before they can be transferred to real projects intuitively, making it a potentially inefficient system for beginners.

However, it is important to note that Toastboard is not designed as a replacement for the Arduino. Rather, it is an in-between education system designed to train primary to middle-school students into intuitively recognizing the systems of electronics, lessening the steep learning curve that current microcontrollers may possess..
# What’s wrong with other non-Arduino engineering kits?
Of course, Toastboard is not the first engineering kit aimed at educating primary-level students. However, there are some key flaws I have found common in many of the kits I have personally used as a child: 
## 1. The product is designed for entertainment, not education
When the target demographic is younger students, it is reasonable that an engineering education kit will be aimed at fostering curiosity and interest rather than advanced, concrete engineering education. However, the problem arises when engineering kits solely promote entertaining projects at the expense of meaningful STEM learning. Instead of introducing fundamental engineering principles through engaging activities, they may function primarily as toys, limiting educational value.
## 2. The product is taken literally rather than intuitively
Many engineering kits encourage students to follow step-by-step instructions to create a predetermined project. While this approach may help beginners achieve a successful outcome and gratification, it can also lead to a reliance on following instructions rather than true, intuitive comprehension of the engineering concepts at hand. As a result, the creative mind of students may be compromised as they begin to see engineering as a set of directions to follow rather than personal creative innovation.
## 3. The product is rigid in functionality and education
Engineering kits are often designed with a fixed set of components that support only a limited range of projects. Students may outgrow the kit quickly, as it provides few opportunities to expand its functionality and explore personal projects. The lack of adaptability in many kits limits the ability to support continued skill development and accommodate learners with different interests and goals.
# Why should anyone care?
Engineering is a high-demand job, projected to increase faster than the average rate of all occupations. Engineering itself shapes the future, and access to education in this field actively determines who has access to shaping the future. Many of today’s technologies come from people who have received the privilege of early exposure and passion. However, if potential talented students never encounter the field due to accessibility or financial restraints, society loses potential innovators. In an increasingly technological world, engineering education should not be reserved for those who can actively afford and access it. By expanding access to engineering education, more students of diverse backgrounds are able to discover their passions and contribute ideas to society shaped by their unique experience. Providing equitable opportunities for students today means building a more creative and capable generation of engineers in the next generation.
# We’ve identified some issues, so what is Toastboard?
Toastboard is a modular microcontroller-controlled electric circuit base kit designed for students to learn electrical concepts intuitively, rather than simply memorizing facts. A Toastboard kit contains three categories of parts necessary to operate: the “toaster” (microcontroller), the “crumb” (breadboard module), and the “jam” (components). Toastboard is aimed at creating an accessible way for primary to middle-school students to learn electrical engineering concepts intuitively, providing a bridge for more advanced systems such as the Arduino. Using lights and visual feedback, the goal of Toastboard is to provide a physical engineering education experience where hardware gives the same visual and intuitive feedback a visual programming language might.

# Toastboard’s one-sentence vision:
“What if learning electrical engineering was as easy as connecting pieces, and as intuitive as building legos?”

# What is Toastboard not?
It’s important to clarify what Toastboard is not, in order to illustrate a clearer image of where and how Toastboard is used. 
## 1. Toastboard is NOT a replacement for Arduino
As mentioned, Toastboard is not created as a replacement for an Arduino or breadboard. In fact, the base of Toastboard itself is a modded Arduino. Toastboard aims at easing beginners, especially younger or self-taught individuals, into the world of software and hardware engineering through intuitive feedback. 
## 2. Toastboard is NOT a step-by-step instruction kit
Although instructions will, of course, be provided, Toastboard itself is meant to foster intuitive understanding of electric systems. Because of this, Toastboard encourages individual learning over results through a process the user did not create themselves. Hints or simple instructions may be given towards projects, but step-by-step instructions will seldom be provided.
## 3. Toastboard is NOT meant to solely solve STEM education 
Toastboard as a concept isn’t meant to replace education in electronics. Rather, it is a system for experimenting with electronics, a tool used alongside other education systems in order to deepen and broaden insight on how engineering concepts can be intuitively understood and applied practically. 
# A quick walkthrough of how Toastboard is used:
Each crumb possesses a light, sockets at the side to connect to other crumbs, and a hole at the top, sending an analog signal and a digital signal. Using the sockets, a crumb can attach itself to another crumb, eventually creating a configuration where electrical signals can pass through the x-axis, but not the y-axis. This configuration of connected crumbs is called a “board”, and represents a breadboard in traditional Arduino engineering. Each electrical signal is assigned a color, with a negative ground current always having a purple color. For example, one node on the board could be connected to a negative ground current given by the microcontroller, called the “Toaster”, and all of the crumbs in that node would glow purple. Meanwhile, another node could be connected to a digital pin, and all of the crumbs in that node would glow yellow. If two different currents are connected to the same node, the crumbs of that node will glow red, indicating an error. In this way, the flow of electrical currents is shown visually, allowing for easier intuitive comprehension. Once a board of crumbs is made, components, called “jam”, can be added. These components include LEDs, servo motors, resistors, etc. which can be clicked into the top sockets on crumbs. If components are added in an incorrect manner (e.x. Both of the pins are connected to the same current, a directional component is placed backwards), a small red LED on each component will light up. However, because there are no constant currents on the Toastboard, the behavior of components must be individually programmed through digital pins. Because the Toaster is a modified Arduino, it can be programmed using the same software as a regular Arduino. Although the Arduino API is quite difficult to understand, several easier alternatives exist, such as Tinkercad Codeblocks and Pictoblox. Toastboard provides an easy, visually intuitive bridge to concepts in Arduino, allowing for an overall easier transition into both software and hardware.
# What are Toastboard’s features, put simply?
Although Toastboard is projected to contain several functions and details, here are the key features which make Toastboard unique:
## 1. Fully modular design
A fully modular Toastboard allows for cost-effectiveness, easy repairs, and flexibility in innovation. Crumbs are fully modular to allow for adaptable designs and formations, allowing the same pieces to be used in distinct projects. Modular crumbs and components are individual blocks which become alive when snapped together, representing the key principle of adaptability in real-world engineering.
## 2. Intuitive connections
Connections give visual and intuitive feedback allowing for obvious and durable, yet intentional relationships. When putting together pieces, lights and visual signals give the response necessary for beginners to comprehensively understand concepts, while still requiring purposeful and logical connections.
## 3. Real-world engineering components, simplified
Toastboard Components are both named after and function as regular, real-world engineering components. For example, LEDs, servo motors, and resistors should be assigned the same function and connections as their real-world counterparts, yet simplified in a way where beginners can understand. Students, when transitioning from Toastboard to a more complex engineering system, should be able to recognize and innovate with the same components used.

These features allow for the progressive open-ended innovation of students rather than rigidly following predetermined projects.
# Design principles of Toastboard
In the process of creating Toastboard, it is important to be able to fairly weigh what belongs and what doesn’t according to its key vision. These are 5 core design principles selected to evaluate Toastboard’s layout and usage:
## 1. Innovation over instruction
Toastboard doesn’t promote rigid instructions on what students should create, but rather encourages individual learning that can be applied practically and personally. Toastboard isn’t designed to tell students what to build, but rather to inspire and make them ask “what can I build next?”
## 2. Honest simplicity
Although some education systems may prefer black box abstractions where internal processes and functions are disguised as magic, Toastboard should be open on how these processes work together to create systems. For example, instead of pretending electricity is a sort of magic power, it should be explained, but visually and intuitively. The simplification of concepts does not mean that they are shrunk.
## 3. Encouraged experimentation
Toastboard is designed not to eliminate mistakes, but rather to help students understand intuitively why these mistakes happen. Experimentation should not be impossible through rigid systems, but rather safe, forgiving, and easy to undo.
## 4. Visible Comprehension
Although good engineering often hides complexity, good education often reveals it. Toastboard should make the invisible, abstract concepts in hardware engineering visible and intuitive. For example, signals traveling could be expressed in LEDs animating, and incorrectly placed modules could be expressed through red lights in surrounding nodes.
## 5. Affordability over complexity
Although it may be useful, Toastboard will never replace formal engineering education, hence why it is designed for the intuitive usage of self-taught individuals. However, this demographic also means that Toastboard must be affordable and easy to modify. When balancing a low-cost product and a more powerful, feature-rich product, a lower cost outcome should always be held to a higher standard, given that the possible features are not overly impactful to learning.
# Demographic of Toastboard
Toastboard is primarily designed for the ease-of-use of curious primary and middle-school students, approximately ages 8-14. Toastboard is also aimed towards self-taught individuals without access to early formal engineering courses and education. However, Toastboard is not solely a toy for children, but an intuitive bridge. Beginners in electrical engineering of all ages should be able to use the product, but Toastboard is not actively designed for more complex levels of education.
# Allocated budget
Because Toastboard is an independent passion project, it is quite difficult to gain funding. Although grants and sponsors may be plausible options in the future, the early prototype and design stages will likely require personal investment. A budget of roughly $200 should be enough, estimating:
3D print materials – $40
Microcontrollers - $50
Components - $40
General electrical parts (wires, clips, etc.) - $30
Extra funds - $40

# Scope of first prototype
Toastboard’s initial prototype should not be a fully fleshed-out design, but rather a simple physical module system exploring whether physical modular electronics can provide a more intuitive and creative introduction to engineering. The prototype will focus on creating a small set of modules allowing beginners to create systems without traditional wiring. A list of basic features for the first prototype could include:
3-5 crumb modules
Basic enclosure
Simple design
Main focus is on how each node can have individual lighting
Simple components
Input modules:
Button
Potentiometer
Output modules:
LED
Servo motor
Arduino-based brain
Programming will be controlled with regular Arduino API

# Conclusion: Why Toastboard?
Early engineering education is a key factor in shaping the engineers of tomorrow’s society. STEM education often lacks the intuitiveness and feedback for self-taught and younger learners to fully grasp engineering concepts and develop curious, innovative passion rather than an ability to rigidly follow instruction. Toastboard is a modular engineering kit aimed at aiding intuitive comprehension for abstract concepts in engineering, allowing beginners to ease into the world of software and hardware engineering in an affordable, visual way. Through a simple node system, collection of components, and easy “plug-and-play” controllers, Toastboard is an independent project aiming to create an education system as easy, yet open-ended as toy building bricks.
