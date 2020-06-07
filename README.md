# classify-dogbreeds-pytorch

## Project Description

This repository contains coding files that will help us determine which CNN model architecture performs best at classifying a dog and its various breeds. This project was completed as part of AI Programming with Python Nanodegree program (Udacity).  

 [**_Udacity GitHub repository_**](https://github.com/udacity/AIPND-revision/tree/master/intropyproject-classify-pet-images) 

### Files Needed to run check_images.py locally

The following files and folders need to be put in the same folder as the **_check_images.py_** python program on your local computer.

* **pet_images**  (folder of 40 pet image)
* **uploaded_images** (a folder you will have to create to hold your uploaded images in that section of the project)
* **classifier.py** (classifier function you will be using to classify the images)
* **dognames.txt** (file that contains all the valid dog names from the classifier function and the pet image files)
* **imagenet1000_clsid_to_human.txt** (dictionary that converts the classifier function ids to text labels)
* **adjust_results4_isadog.py** (a program that contains the **adjust_results4_isadog** function )
* **calculates_results_stats.py** (a program that contains the **calculates_results_stats** function)
* **classify_images.py** (a program that contains the **classify_images** function )
* **get_input_args.py** (a program that contains the **get_input_args** function )
* **get_pet_labels.py** (a program that contains the **get_pet_labels** function )
* **print_results.py** (a program that contains the **print_results** function )
* **run_models_batch.sh** (a bash script that will run check_images.py sequentially for all 3 model architectures and output their results to text files - on Unix/Linux/OSX/Project Workspace from a terminal window)
* **run_models_batch.bat** (a batch script that will run check_images.py sequentially for all 3 model architectures and output their results to text files - on Windows from the Anaconda Prompt window)
* **run_models_batch_uploaded.sh** (a bash script that will run check_images.py sequentially for all 3 model architectures  on the uploaded images folder and output their results to text files - on Unix/Linux/OSX/Project Workspace from a terminal window)
* **run_models_batch_uploaded.bat** (a batch script that will run check_images.py sequentially for all 3 model architectures on the uploaded images folder and output their results to text files - on Windows from the Anaconda Prompt window)
* **test_classifier.py** (an example program that demonstrates how to use the classifier function)
* **print_functions_for_lab_checks.py** (a program that contains functions that will allow you to check your code)

## Running the batch files locally
In anaconda prompt, execute **_run_models_batch_** or **_run_models_batch_uploaded_** file that will compute **_check_images.py_** for all CNN architectures. For windows use .bat  and not .sh files

## Dependencies

Each directory has a `requirements.txt` describing the minimal dependencies required to run the notebooks in that directory.

### pip

To install these dependencies with pip, you can issue `pip3 install -r requirements.txt`.