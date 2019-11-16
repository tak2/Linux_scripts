# Linux_scripts
Linux scripts to ease the setup and workflow

stackedit.io

# Anaconda on windows cheat sheet

Hi there this is an easy guide to  start anaconda on windows 

# Start a new environment in different folder 
environments is one of the best features of anaconda however it takes a lot of space (as am using a small SSD for the primary drive) its takes a lot of space 

first navigate using anaconda prompt to the desired location of env folder 
then

conda create --prefix ./envs
conda activate ./envs
conda config --set env_prompt '({name})'
