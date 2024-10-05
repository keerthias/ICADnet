# ICADnet: Prior Knowledge-based Framework for Intracranial Aneurysm Detection on TOF-MRA using Coupled CNN
ICADnet is  a prior knowledge-based framework for aneurysm detection from TOF-MRA volume.  It embeds task-specific domain knowledge as a function or operator into the deep learning model to develop a framework for aneurysm detection with limited training samples and, thereby, improve the generalization and  efficiency of the CAD systems. 

This repository contains all the necessary files and configurations required to set up and run ICADnet, enabling users to easily deploy and validate the network in their own environment.
# Usage
 You can run the ready-to-use ICADnet docker container with the following command:
```bash
docker run -dit --network none -v [path_to_input_directory]:/input:ro -v /output name_of_the_docker_container.'''

The -v options map the input folder into the container at /input, read-only. The last -v creates an output directory. This command outputs the Container ID, which you can also look up with:

