![Alt text](https://github.com/CLAIR-LAB-TECHNION/CLAIR-TMP-Tutorials/blob/main/assets/figures/messy-kitchen-robot.png)

# Introduction to Task and Motion Planning and Learning
Our focus is on exploring settings in which robotic agents need to perform complex tasks that require high-level reasoning and planning, on the one hand, and an understanding of how to move and operate in the physical environment, on the other hand. Since we are interested in complex tasks, simply learning an optimal policy from previously performed trajectories is insufficient.

In our settings of interest, we require both the ability to perform **task planning**, which focuses on high-level decision-making and on choosing a sequence of actions that should be executed to achieve a goal, and **motion planning**, which deals with the low-level details of generating feasible motions to execute those tasks safely and efficiently.

We also require our agent to learn from its own experience and from experience collected by others to improve its performance. 

# Running the Tutorials
The tutorials are provided in the form of Jupyter notebooks, suitable for running online via Google Colab. Basic knowledge of Python and PDDL is required.
All necessary installations are performed when running the first few cells of each notebook.
The notebooks can be found here:

https://github.com/CLAIR-LAB-TECHNION/CLAIR-TMP-Tutorials/tree/main/notebooks

If you would like to run the notebooks locally on your machine, you can download them, but some installations may be required (e.g., numpy).
Otherwise, just click on "Open in Colab" at the top of each notebook.

