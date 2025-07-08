# intro-HPC-bootcamp-2025
This repository contains information related to the Intro to HPC Bootcamp held in person at Argonne National Laboratory (ANL) in August 2025. The Bootcamp is hosted by the Department of Energy (DOE) Advanced Scientific Computing Research (ASCR) Computing Facility at ANL Leadership Computing Facility (ALCF), in collaboration with the Lawrence Berkeley National Lab (NERSC) and Oak Ridge National Lab (OLCF).

## Links and Study Materials

* [Bootcamp public page](https://intro-hpc-bootcamp-stg.alcf.anl.gov/)
* [Perlmutter](https://docs.nersc.gov/systems/perlmutter/)
* [OLCF Intro to Python repo](https://github.com/olcf/foundational_hpc_skills/tree/master/intro_to_python)
* [Pandas tutorial](https://www.activestate.com/resources/quick-reads/what-is-pandas-in-python-everything-you-need-to-know/)
* [Example interactive Notebooks for data research from Environmental Enforcement Watch](https://www.environmentalenforcementwatch.org/data/notebooks)

## Presentations
* Monday
  * Intro to HPC Bootcamp Welcome, Paige Kinsley
  * Welcome to the World of High-Performance Computing, Mike Papka
  * High-Performance Computing Keynote, Kevin Brown
  * Projects Overview, Paige Kinsley
* Tuesday
  * Introduction to Parallelization, Rebecca Hartman-Baker
  * Artificial Intelligence Keynote
* Wednesday
  * Introduction to Data Visualization, Kristy Streu
  * [Introduction to Regression Analysis and Applications to AI, Wilbur Ouma](https://github.com/Wilber/hpcbootcamp_regression)
* Thursday
  * Giving a Good Presentation, Paige Kinsley
* Friday

 
## Projects
| **Project (and link project description)**                                                                                                                                                                                                                                    | Project Page                                                                              | Institution              | **Lead**                                      |
|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |:-----------------------------------------------------------------------------------------:|:------------------------:|:---------------------------------------------:|
| [Project 1: Analyzing the Impact and Applications of Fusion Energy for the Future](https://intro-hpc-bootcamp-stg.alcf.anl.gov/project-1-analyzing-impact-and-applications-fusion-energy-future)                                                                                                                                           | [Fusion Energy](https://github.com/AI4EnergyJustice/Tutorials)                                                                                      | NERSC                      | Charles Lively, Helen He, Kelly K. Rowland, Rebecca Hartman-Baker, Lipi Gupta                                  |
| [Project 2: Understanding and Optimizing Energy Usage from HPC Centers](https://intro-hpc-bootcamp-stg.alcf.anl.gov/project-2-understanding-and-optimizing-energy-usage-hpc-centers)                                                                                                                                                                   | [Energy Usage for HPC](https://saforem2.github.io/climate-analysis)                           | NERSC                      | Charles Lively, Helen He, Kelly K. Rowland, Rebecca Hartman-Baker, Lipi Gupta          |
| [Project 3: The Anatomy of a Power Outage](https://intro-hpc-bootcamp-stg.alcf.anl.gov/anatomy-power-outage)                                   | [Power Outage](https://github.com/alvarovm/solarcelldata)                                                                                      | ORNL                      | Suzanne Parete-Koon, Thomas Fillers, Nrushad Joshi                     |
| [Project 4: Short-Term Load Forecasting Using Machine Learning](https://intro-hpc-bootcamp-stg.alcf.anl.gov/short-term-load-forecasting-using-machine-learning)                                                             |  [Load Forecasting](https://sites.google.com/lbl.gov/nerschpcbootcamp2023/nerscenergyjustice2023) [(Project 4 Notebooks)](https://github.com/NERSC/intro-HPC-bootcamp-2023/tree/main/Project4)                                                                                                                                                       | ORNL                    |  Suzanne Parete-Koon, Thomas Fillers, Nrushad Joshi                                   |
| [Project 5: Large Language Models for Science](https://intro-hpc-bootcamp-stg.alcf.anl.gov/project-5-large-language-models-science)   | [LLMs for Science](https://sites.google.com/lbl.gov/nerschpcbootcamp2023/nerscenergyjustice2023) [(Project 5 Notebooks)](https://github.com/NERSC/intro-HPC-bootcamp-2023/tree/main/Project5)                                                                                      | ANL                    | [Sam Foreman](https://samforeman.me)                                |
| [Project 6: Evaluating Large Language Models for HPC Education](https://intro-hpc-bootcamp-stg.alcf.anl.gov/evaluating-large-language-models-hpc-education)                                                                             | [Github](https://github.com/secondspass/power_outages_medically_vulnerable_populations/)  | ANL                     | Murat Kerceli                                |
| [Project 7: Computational Design of Low-Cost/High-Efficiency Solar Cells](https://intro-hpc-bootcamp-stg.alcf.anl.gov/solar-power-affordable-housing-through-computational-design-low-costhigh-efficiency-solar-cell)                                                                                                                                                       | [Github](https://github.com/suzannepk/power_outages_socioeconomics-)                      | ANL                     | Alvaro Vazquez-Mayagoitia                           |

## Working on Project in Groups

* Besides those projects materials provided via links in the above table, each project has also prepared the project descriptions and data in the m4388 project area on the Community File System (CFS) on Perlmutter at `/global/cfs/cdirs/m4388/Project*-<name>`, such as `Project2-ClimRR`.
* Students who work on Project X Group Y will work in a shared directory in CFS at /global/cfs/cdirs/m4388/Project*-Group*, such as `Prj2-GroupC`.
* Using Prj2-GroupC as an example, you can run this command to copy over the entire Project, after login to Perlmutter:
  ```
  cd $CFS/m4388/Prj3-GroupC
  cp -r $CFS/m4388/Project2-ClimRR .
  ```
* Any student who would like to do some individual tests can work in their own scratch directory:
  ```
  cd $SCRATCH
  cp -r $CFS/m4388/Project2-ClimRR .
  ```
* The following are the compute node reservations available during the boot camp (in Pacific time):
  * Monday, 3 pm - 5 pm, reservation name `intro_hpc_aug7`
  * Tuesday, 10:30 am - 5 pm, reservation name `intro_hpc_aug8`
  * Wednesday, 1:30 pm - 5 pm, reservation name `intro_hpc_aug9`
  * Thursday, 1 pm - 10 pm, reservation name `intro_hpc_aug10`

## Study Materials

* [OLCF Intro to Python repo](https://github.com/olcf/foundational_hpc_skills/tree/master/intro_to_python)
* [Pandas tutorial](https://www.activestate.com/resources/quick-reads/what-is-pandas-in-python-everything-you-need-to-know/)
* [Example interactive Notebooks for data research from Environmental Enforcement Watch](https://www.environmentalenforcementwatch.org/data/notebooks)
