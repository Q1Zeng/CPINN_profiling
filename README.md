# CPINN_profiling

This is my code to profile one of the experiments in [CPINN repo](https://github.com/comp-physics/CPINN). Testing purpose only.

To analyze the runtime, I used `cProfile` and [snakeviz](https://pypi.org/project/snakeviz/). 
The visualization can be reproduced by typing 

    snakeviz profile_cpu.stats
or

    snakeviz profile.stats
in command line.

You can create a new virtual requirement by using `Pip` and the `requirement.txt` file.

    pip install -r requirement.txt

To measure the energy consumption, I ran these experiments locally in my laptop and use 

    powercfg /batteryreport

in command line to track the battery usage.