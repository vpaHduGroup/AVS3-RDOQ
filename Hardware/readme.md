

### Project Structure

The tree map of this hardware architecture is shown as below:

> - result **#test vectors**
> - RTL **#all RTL code**
>   - sim **#simulation files**
>   - source **#source code**

### Tips

The simulation file in this project uses relative paths to read the test vectors from the **result** file. When establishing the simulation project, pay attention to whether the path to the read file is placed correctly.