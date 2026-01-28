# Creating an intermediate layer between a high-level scheduler and a low-level MPC controller

For now, we are just understanding the basic installation setup.
To keep things similar to the project, follow this setup
1. Use Ubuntu 22.04. This has been done with dual boot by the creators of this project.

2. Pytohn 3.10

3. Install docker. Follow the installation instruction on the docker website.

4. Install ducktietown shell. **NOTE:** It is a pip install, not from some website

5. Clone this repo

6. To compile, run 
```bash
dts devel build -f
```

7. To run,
```bash
dts devel run
```


**NOTE:** If you want to develop software that uses ROS, check out
[this template](https://github.com/duckietown/template-ros).
