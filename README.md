# chair-training

## Prerequisite
You will need to have `conda` installed on the system. Miniconda should suffice
[install miniconda](https://docs.conda.io/en/latest/miniconda.html)

### Clone the repo
```bash
git clone git@github.com:upcycling-kandidat/chair-training.git
cd chair-training
```
### Create a new conda environment
```bash
conda env create --file environment.yml
``` 
This will look for the environment.yml file and create a new environment called chair-training. To activate this new environment, run the following command:
```bash
conda activate chair-training
```

## Datasets
The datasets used for training are available on Roboflow. The datasets are available in the following links:
- https://universe.roboflow.com/yolo-6y5cv/chair-scratches/dataset

## Environment
Conda was used to setup a local testing environment

Update the environment.yml file with the new dependencies and run the following command to update the environment:
```bash
conda env update --file environment.yml --prune
```

- https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#updating-an-environment
