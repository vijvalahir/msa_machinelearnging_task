# msa_machinelearnging_task 
# Making a Machine Learning Model to get a Geekbench 6 Score for Intel Raptor Lake Cpus

## Dataset
The dataset is taken from the official geekbench website.

## Workflow
The model works on the concept of multiple linear regression.

plotting: No of cores and boost frequency on the X axis
          Geekbench 6 score on the Y axis 
          
The model allows the users to input no of cores and frequency to their liking makeing the model very useful in virtualization giveing users the idea of the performance when they split the cores.

## Example
Entering core i9 13900k specifications: cores = 24 frequency = 5.8 Ghz
we get the output of 20962.46 which is within 1000 points of the geekbench 6 score proving the model works.

## Known Issues
The model only works for intel raptor lake desktop cpu, other processors wont work because of having a different architecture and powerdraw.
