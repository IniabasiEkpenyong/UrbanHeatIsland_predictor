# UrbanHeatIsland_predictor
Using satellite data from the Landsat and Sentinel2 satellites and employing probabilistic models to predict instances of the Urban Heat Island effect in Manhattan and the Bronx.

# Set Up  

The set up is done so far with a conda enviroment. In your terminal make sure you are in the home directory of the project and run

$ conda env create -f environment.yml

This should create a conda enviroment called UHI, which contains all the dependencies I've used so far to extract the data and run the code. You can activate this enviroment by calling 

$ conda activate UHI

If someone adds a bit of code that requires aditional dependencies, please update the yaml file or creal a new one for reproducibility purposes. 

# Data

Unfortunately the satellite data used to run the models was too big to store in github. Everyone should be able to get the data in their local machine by running either the UHI_Experiment_Sample_Benchmark_Notebook_V7_2.ipynb file or the testing.ipynb file in the Code repository. The testing file stores all the data from the sattelite spectral bands and the UHI_Experiment_Sample_Benchmark_Notebook_V7_2.ipynb file stores only select ones. You can also peruse the methods of data extracting and store the data you may want by modifying the notebooks in your local or creating an entirely new one. 
