# Context-based-Query-Answering-for-Stackoverflow-Q-A

## About
Implementation of Context-based Query Answering using LDA and LSI. This model will generate and provide answers on online forums such as Stackoverflow based on the pattern of previous answers given by users.

## Dataset Used
The [Stackoverflow, Security & Sustainability - 10M QAs](https://www.kaggle.com/datasets/lucmichalski/stackoverflow-stackexchange-dataset-10m-qa) dataset from Kaggle

## Workflow
![image](https://user-images.githubusercontent.com/57147597/191290075-14e9d726-a136-463b-a742-6370c8347f14.png)

## Technologies Used
1. **Python** - For modelling LDA and LSI
2. **MongoDB** - For pre-preocessing the data
3. **Anvil** - For creating the GUI

## Steps to Run the GUI
1. Download the file ***ContextBased_QueryAnswering.ipynb***
2. Download all the files in the ***Saved Models*** folder and store it in the same folder as the **.ipynb** file
3. Run all the cells in the **.ipynb** file
4. The very last cell will have a link to the Anvil GUI. Click on this
5. Once the GUI window is open, type a question in the text box and click on the **FIND ANSWER** button to find the best answer

![image](https://user-images.githubusercontent.com/57147597/191292246-62af7359-0fac-4ad5-9a00-632f4fba7a3d.png)


