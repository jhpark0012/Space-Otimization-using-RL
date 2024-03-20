# Space-Otimization-using-RL
[Deep Learning Application] Space Otimization using Reinforcement Learning : Solve Pentomino Puzzle


## Period
23.09.12 ~ 23.11.08

## Background
According to Korea Integrated Logistics Association, after the COVID pandemic, the total revenue of the parcel delivery market continues to increase.

To handle these issues, there are many automated pick and place systems to solve the Bin Packing Problem.

However, this method relies on heuristic algorithms, depending on the quality of heuristic functions. 

To solve these problems, we defined the situation as a 'space optimization'.

We need to place items in a limited space, deciding how to fill the space most optimally with items of various sizes and shapes.

We found a similar situation in the Pentomino puzzle, where different pieces need to fit into a given shape. 

We decided to simulate and solve this problem using reinforcement learning, reducing a 3D real-world problem to a 2D puzzle.



## Role 
| 박재현 | 장지형 | 김동 |
|:---:|:---:|:---:|
| implement baseline | impletement train code | implement environment code |



## File
* EDA.ipynb : EDA file of each subject's data
* Preprocessing.ipynb : Preprocessing file
* sleep_df.pkl : Data from all subjects after preprocessing
* Modeling.ipynb : Sleep classification modeling and results file by subject


## Result
As a result of the 2-class classification, it showed a high f1 score overall, indicating that it was successfully modeled.

However, the 4-class classification showed a low score, which is considered a data imbalance problem, and it is expected that solving this problem will increase the accuracy of the 4-class classification.


  
## Expected Outcomes

If parcel companies use RL for space optimization, then they can optimize item placement in warehouses and delivery trucks, making warehouse operations more efficient. 

This not only facilitates automation processes but also minimizes use of truck, reducing energy consumption and environmental impact.

This also has positive effect for workers. Efficiently placed items allow workers to perform tasks with less intensity and in a more comfortable environment.

Consumers can also expect faster and improved delivery services.

In conclusion, we can say that the application of our project can positively impact the entire process in logistics.

