# Andrea Torti

I obtained my Master's Degree in Computer Science and Engineering @ Politecnico di Milano in 2025 and I specialized in low-level programming and optimization, with some computer graphics, computer vision, robotics, embedded development and AI sprinkled here and there. I even wrote a lot of raw CUDA code and obtained a couple certifications from Nvidia!

During my academic career, I loved hands-on projects the most, where I could have control over every piece of the software I was developing and take pride in the results. Most of them were group projects, and that's where I discovered that I perform the best working with a team on tough problems and under strict deadlines. Some were developed on Windows, most on Linux, but I also daily macOS.

Here's a preview of some of my work, but there's always something more that's work in progress... always building, always learning!

CFD Software written from scratch entirely in C++! Can run on CPU (Even in parallel with OpenMP) or on your NVIDIA GPU!
![alt text](ball-80.gif)
On GPU, performance was the top priority, so I chose the structure of arrays approach. On CPU, arrays of structures is used for better code readability.
![alt text](rho-coalescence.png)
Yes, the performance was profiled with callgrind. Down to the single function call.
![alt text](callgrind-lid-driven-100-cpu-parallel.png)
Did you think I wouldn't profile the GPU too?
![alt text](cuda-kernels-detail.png)
---
Onto the next one. The data you see is from an Arduino's motion sensors.
![alt text](pass_shoot.png)
My friend chatgpt wrote some python software to cut 1-second samples...
![alt text](snip_snip.gif)
And I trained a tensorflow deep learning model to recognize what the person wearing the arduino was doing! How cool is that? Oh and it runs ON the actual arduino, if that wasn't enough.
![alt text](confusion_matrix.png)
---
Do you like trading? Here's a little trading game for you! Done over a weekend, needs some polish. At least it works!
![alt text](game.png)
---
Oh yeah I take a Vulkan course at university. Here's a little game running on an engine... written from scratch.
![alt text](gif3.gif)