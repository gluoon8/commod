# Project-III

## Brief description of the project
This project involves the development of a simple molecular dynamics program to simulate a Van der Waals gas of particles. The project requires collaborative work from all team members to ensure the successful implementation of a working program code. Each team member has a specific task that contributes to the overall functionality of the program.

## Team Members and Responsibilities

1. **Aina Gaya**: Integration Newton's equations.
2. **Albert Plazas**: Compute the forces for a Van der Waals interaction.
3. **Manel Serrano**:  Post-processing of data, statistics, and visualization.
4. **Anna Monclús**:  Initialize the configuration and define boundary conditions. Also coordinates the GitHub repository.


## Prerequisites
To execute the program, there are some pre-requisites:
- Make: to execute the program (https://www.gnu.org/software/make/#download)
- Gfortran: to run the MD simulation. (https://gcc.gnu.org/wiki/GFortran)
- Python 3.x : to generate the plots after simulation
  - Numpy (https://numpy.org/install/)
  - Matplotlib (https://matplotlib.org/stable/users/installing/index.html)


## How to

1. Clone repository to your local host
2. Use `make` or `make help` to see the available commands.
3. Before starting a simulation, change your parameters in *namMD.nml* file  
4. To carry out the simulation, use `make run` and the program will be compiled and run. 
5. Data is generated in *.dat* files. If you want to generate figures, use `make plot`

> [!TIP]
> There are some ways to clean generated files, have a look at `make clean`, `make cleandata` and `make cleanplot`.


## Help 
                          

- Commands:                                                       
  
  - `make run`: Compiles needed files and also runs the program.     
 
  - `make plot`: Plots the output data:                              
   - Epot, Ekin, Etot vs time                                   
     - Momentum vs time                                           
     - T vs time                                                  
     - Pressure vs time                                           
  - `make all`: Compiles the program and creates executable MD.exe   
 
  - `make clean`: Removes the modules, objects and executable        

  - `make cleandata`: Removes data files                             
 
  - `make cleanplot`: Removes plot files                             
 



## Contributors
|  Anna Monclús  |  Aina Gaya  |  Albert Plazas   |  Manel Serrano  |
| -------------- | ----------------- | ------------------ | ------------- |
| ![anna-mr98](https://github.com/Eines-Informatiques-Avancades/Project-III/tree/master/docs/anna-mr98.png "anna-mr98") | ![ainagaya](https://github.com/Eines-Informatiques-Avancades/Project-III/tree/master/docs/ainagaya.png "ainagaya") | ![Alplalo](https://github.com/Eines-Informatiques-Avancades/Project-III/tree/master/docs/Alplalo.png "Alplalo") | ![gluoon8](https://github.com/Eines-Informatiques-Avancades/Project-III/tree/master/docs/gluoon8.png "gluoon8") |
| [anna-mr98](https://github.com/anna-mr98)                                 | [ainagaya](https://github.com/ainagaya)| [Alplalo](https://github.com/Alplalo)                                  | [gluoon8](https://github.com/gluoon8)                                  |



