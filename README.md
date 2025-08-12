# intro-HPC-bootcamp-2025
This repository contains information related to the Intro to HPC Bootcamp held in person at Argonne National Laboratory (ANL) in August 2025. The Bootcamp is hosted by the Department of Energy (DOE) Advanced Scientific Computing Research (ASCR) Computing Facility at ANL Leadership Computing Facility (ALCF), in collaboration with the Lawrence Berkeley National Lab (NERSC) and Oak Ridge National Lab (OLCF).

## Links and Study Materials

* [Bootcamp public page](https://intro-hpc-bootcamp.alcf.anl.gov/)
* [Perlmutter](https://docs.nersc.gov/systems/perlmutter/architecture/)
* [OLCF Intro to Python repo](https://github.com/olcf/foundational_hpc_skills/tree/master/intro_to_python)
* [Pandas tutorial](https://www.activestate.com/resources/quick-reads/what-is-pandas-in-python-everything-you-need-to-know/)
* [Example interactive Notebooks for data research from Environmental Enforcement Watch](https://www.environmentalenforcementwatch.org/data/notebooks)

## Presentations and Tutorials
* Monday
  * Intro to HPC Bootcamp Welcome, Paige Kinsley
  * Welcome to the World of High-Performance Computing, Mike Papka
  * High-Performance Computing Keynote, Kevin Brown
  * Projects Overview, Paige Kinsley
* Tuesday
  * Introduction to Parallelization, Rebecca Hartman-Baker
  * AI Keynote: Artificial Intelligence to Determine Actionable Cancer States, Alexander Pearson , Associate Professor of Medicine, University of Chicago
* Wednesday
  * Introduction to Data Visualization, Kristy Streu
  * [Introduction to Regression Analysis and Applications to AI, Wilbur Ouma](https://github.com/Wilber/hpcbootcamp_regression_AI)
* Thursday
  * Giving a Good Presentation, Paige Kinsley
 
## Projects
| **Project (and link project description)**                                                                                                                                                                                                                                    | Project Github Page                                                                              | Institution              | **Lead**                                      |
|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |:-----------------------------------------------------------------------------------------:|:------------------------:|:---------------------------------------------:|
| [Project 1: Analyzing the Impact and Applications of Fusion Energy for the Future](https://intro-hpc-bootcamp.alcf.anl.gov/project-1-analyzing-impact-and-applications-fusion-energy-future)                                                                                                                                           | [Fusion Energy](https://github.com/NERSC/DOE_HPC_Bootcamp_2025)                                                                                      | NERSC                      | Charles Lively, Helen He, Kelly K. Rowland, Rebecca Hartman-Baker, Lipi Gupta                                  |
| [Project 2: Understanding and Optimizing Energy Usage from HPC Centers](https://intro-hpc-bootcamp.alcf.anl.gov/project-2-understanding-and-optimizing-energy-usage-hpc-centers)                                                                                                                                                                   | [Energy Usage for HPC](https://github.com/NERSC/DOE_HPC_Bootcamp_2025)                      | NERSC                      | Charles Lively, Helen He, Kelly K. Rowland, Rebecca Hartman-Baker, Lipi Gupta          |
| [Project 3: The Anatomy of a Power Outage](https://github.com/suzannepk/anatomy_of_a_power_outage)                                   | [Power Outage](https://github.com/suzannepk/anatomy_of_a_power_outage)                                                                                      | ORNL                      | Suzanne Parete-Koon, Thomas Fillers, Nrushad Joshi                     |
| [Project 4: Short-Term Load Forecasting Using Machine Learning](https://github.com/Joshina-ORNL/BuildingsBenchTutorial)                                                             |  [Load Forecasting](https://github.com/Joshina-ORNL/BuildingsBenchTutorial) [(Project 4 Notebooks)]([https://github.com/NERSC/intro-HPC-bootcamp-2023/tree/main/Project4](https://github.com/Joshina-ORNL/BuildingsBenchTutorial))                                                                                                                                                       | ORNL                    |  Suzanne Parete-Koon, Thomas Fillers, Nrushad Joshi                                   |
| [Project 5: Large Language Models for Science](https://intro-hpc-bootcamp.alcf.anl.gov/project-5-large-language-models-science)   | [LLMs for Science](https://saforem2.github.io/intro-hpc-bootcamp-2025/)                                                                                       | ANL                    | [Sam Foreman](https://samforeman.me)                                |
| [Project 6: Evaluating Large Language Models for HPC Education](https://intro-hpc-bootcamp.alcf.anl.gov/evaluating-large-language-models-hpc-education)                                                                             | [LLMs for HPC](https://github.com/keceli/IntroductionToHPCBootcamp)  | ANL                     | Murat Keçeli                                |
| [Project 7: Computational Design of Low-Cost/High-Efficiency Solar Cells](https://intro-hpc-bootcamp.alcf.anl.gov/solar-power-affordable-housing-through-computational-design-low-costhigh-efficiency-solar-cell)                                                                                                                                                       | [Design of Solar Cells](https://github.com/alvarovm/solarcelldata)                      | ANL                     | Alvaro Vazquez-Mayagoitia                           |

## Working on Project in Groups

* Besides those projects materials provided via links in the above table, each project has also prepared the project descriptions and data in the m4388 project area on the Community File System (CFS) on Perlmutter at `/global/cfs/cdirs/m4388/Project*`, such as `Project2`.
* Students who work on Project X Group Y will work in a shared directory in CFS at /global/cfs/cdirs/m4388/GroupXY, such as `Group2A`.
* Using Group2A as an example, you can run this command to copy over the entire Project, after login to Perlmutter:
  ```
  cd $CFS/m4388/Group2A
  cp -r $CFS/m4388/Project2 .
  ```
* Any student who would like to do some individual tests can work in their own scratch directory:
  ```
  cd $SCRATCH
  cp -r $CFS/m4388/Project2 .
  ```
* The following are the compute node reservations available during the boot camp (in Central time):
  * Monday, 2:30 pm - 5:30 pm, reservation names `intro_hpc_day1` (for all projects) and `cpu_day1` (for project 3)
  * Tuesday, 3:00 pm - 5:30 pm, reservation names `intro_hpc_day2_pm` (for all projects) and `cpu_day2` (for project 3)
  * Wednesday, 9:00 am - 5:30 pm, reservation names `intro_hpc_day3` (for all projects) and `cpu_day3` (for project 3)
  * Thursday, 12:00 pm - 8:30 pm, reservation names `intro_hpc_day4` (for all projects) and `cpu_day4` (for project 3)

## Study Materials

* [OLCF Intro to Python repo](https://github.com/olcf/foundational_hpc_skills/tree/master/intro_to_python)
* [Pandas tutorial](https://www.activestate.com/resources/quick-reads/what-is-pandas-in-python-everything-you-need-to-know/)
* [Example interactive Notebooks for data research from Environmental Enforcement Watch](https://www.environmentalenforcementwatch.org/data/notebooks)
