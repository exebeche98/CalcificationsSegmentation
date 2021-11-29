Preprocessing of CT images. Training models with and without generators,
in my case the best results were obtained without generators.
There have been many experiments with different model hyperparameters.
An ensemble of the best models. Models and pictures can be found on google drive.
https://drive.google.com/drive/u/2/folders/1VJzlEbuswMTun42n9MrcZ_VHyHgVW6a3
The pictures were marked up manually and the classes are very unbalanced, which complicates the task.
It is important to note that calcinate can have a density below 800 HU,
but on the masks they are marked only with a density of 800 or more. 
In the normal range of densities, they are almost indistinguishable, 
so it is desirable that the dataset be labeled by specialists.