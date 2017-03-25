# UM Data Science Starter Kit for RapidMiner 
Datasets included:
1. Iris (https://www.kaggle.com/uciml/iris)
2. Mushrooms (https://www.kaggle.com/uciml/mushroom-classification)

## Info
- Bear in mind these datasets are for your introduction to data science and applied machine learning.
- Try to explore rapidminer as much as possible.
- Decision Tree is not the only classifier you can use to train you model.

## Instructions on how to use the data and Rapidminer.

1. Open Rapidminer.
2. Go to “File”,  and choose “Import Process”. Navigate to the directory and choose UM_DS_starterKit.rmp
3. Process is now loaded.
4. Now, to load the csv file into the process. Clicking on the “Read CSV” module.
5. After you click on the module, on the right hand side of the Rapidminer’s view, there is “Parameters” section.
6. Click “Import Configuration Wizard”. A Data Import Wizard will be launch.
7. STEP 1: Navigate to the directory and choose your csv file for example “iris.csv”. Press NEXT.
8. STEP 2: You gonna see a table with column separator selection. Since data is already structured, press NEXT.
9. STEP 3: This is annotation wizard. Just press NEXT.
10. STEP 4: This step is important. Find the class column or the target column that you want to predict. For example, in the iris dataset (iris.csv), the target column is the “Species” column. It’s because we are trying to predict that specific column (Species). So that will be our class. In this step, you need to find the class column and change “attribute” to “label”. Sometimes, in machine learning, we can also refer to class as label. In Rapidminer, we use “label”. So, the “Species” column will be our “label”. All other columns are attributes(features).
11. Press FINISH.
12. Data is now loaded into the Read CSV module. Now, press the  PLAY SYMBOL button at the top to run the process.
13. You will then be directed to the “Results” views. Here you can see the results for all of the output that..
14. You can switch between the Design and Results tab back and forth easily.
15. Try explore.
16. If you have any questions, shoot it out in the group !

Thanks! 
