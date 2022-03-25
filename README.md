# Feature-selection-Multivariate-Regression-SAS-Miner

**Dataset:** country_wise_latest.csv (COVID-19 Cases: https://www.kaggle.com/datasets/imdevskp/corona-virus-report)

**Steps:**
1. Create Diagram
2. Drag File Import node from sample and import country_wise_latest.csv
3. Edit Variables, set Deaths as Target
  - ![image](https://user-images.githubusercontent.com/98597962/160187038-cd2e88ac-7538-487a-8e4b-f8346e00bca0.png)
5. Select Input features
6. Drag data partition node from sample
7. select ratio of train, validate, and test set (60,30,10)
8. Drag regression node from model tab
9. Select Model selection, input coding, and regression type from regression node properties
  - ![image](https://user-images.githubusercontent.com/98597962/160187349-ae2e8e5a-c5bd-429e-a0c1-26ad4b30e31c.png)
11. Run Regression node and view the results 

**Results:**

- ![image](https://user-images.githubusercontent.com/98597962/160186734-935dc53e-255e-4ae4-9927-6ee22798efa8.png)
- ![image](https://user-images.githubusercontent.com/98597962/160197362-178a6dbf-1571-4776-ab87-7cd5282f8326.png)



