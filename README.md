# ICADnet: Prior Knowledge-based Framework for Intracranial Aneurysm Detection on TOF-MRA using Coupled CNN
ICADnet is  a prior knowledge-based framework for aneurysm detection from TOF-MRA volume.  It embeds task-specific domain knowledge as a function or operator into the deep learning model to develop a framework for aneurysm detection with limited training samples and, thereby, improve the generalization and  efficiency of the CAD systems. 

This repository contains all the necessary files and configurations required to set up and run ICADnet, enabling users to easily deploy and validate the network in their own environment.
# Usage
 You can run the ready-to-use ICADnet docker container with the following command:

'''bash
docker run -dit --network none -v [TEST-INPUT]:/input:ro -v /output crownchallenge/[TEAM-NAME]_task

Note: The COPY, ADD, and RUN statements add a new layer to your image. Try to combine commands into a single RUN statement; separate this only if it is required for readability. Our Python code is saved next to this Dockerfile in the folder `src/run.py`. With the following command, we build a Docker container from our Dockerfile and the Python source code:

```bash
docker build -f Dockerfile -t crownchallenge/[TEAM-NAME]_task1 .

