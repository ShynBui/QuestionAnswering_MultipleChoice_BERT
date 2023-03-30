# An approach to the problem of automatic answers to the English reading comprehension test
The project is a machine learning model based on BERT architecture to find the answer to a Reading comprehension problem with multiple-choice answers. The ultimate goal of this work is to create a solution that helps solve problems to answer Reading comprehension problems without any reasoning or knowledge. The model focuses on solving Reading comprehension multiple choice questions of the easy and medium form (Factoid), suitable for students in grades six and seven. The model will help solve the self-explanatory WH question from a given text.

# How to Install and Run the Project
# Option1: 
        Install Jupyter Notebook on your computer.
        Download the .ipynb file from the GitHub repository.
        Open the .ipynb file in Jupyter Notebook.
        Run command boxes to perform actions in files.
# Option2:
        Open Google Colab.
        Download the .ipynb file from the GitHub repository.
        Open the .ipynb file in Google Colab.
        Run command boxes to perform actions in files.
        
# How to Use the Project
While you open the interface with gradio
You will have six tables to enter data. Respectively: 
+ Context (A given passage to model reading comprehension)
+ Question (Question regarding given data)
+ Four answers (A, B, C, D)
After filling in those six tables, please click the submit button below.
The model will give you the correct answer in the "output" box.

# Data for test
1.
Context: The same " xx " system is used for other parts of the testing sites in NV. The Original Rectangular Base from 6 to 10 miles is now part of the so-called " room ", which is the rectangular base from 23 to 25.3 miles of prohibited air space. The area is connected to the nts indoor road network, and the road road leading south to mi and west to flat. The North-East of the lake leads to a well-maintained, well-maintained lake c road that runs through the Humboldt Hills. Previously it was leading to mines in the Jerome Basin, but it has improved since its closure. The Zigzag road passes through security checkpoints, but the prohibited area around the base extends more to the east. After exit from the prohibited area, lake c road descends east to the valley of the tikaboo valley, passing through the entrances to the dirt roads of several cattle farms, before they meet with main road 375, on the " off-Earth highway ", to the south of the Rachel. <br>
Question: Where does the lake lake road lead to the lake?<br>
Answer A: South East<br>
Answer B: North and South East<br>
Answer C: North with  South East<br>
Answer D: North East<br>
**True answer:** D. North East<br>

2.
Context: Lake C was used for artillery shelling and artillery training during world War II, but was then abandoned until April 1955, when it was selected by the team of the Luke as a perfect location to test the u-2 spy plane. The bottom of the lake provided the perfect tape that can do annoying aircraft tests, the height of the mountains of the valley of the grant valley and the nts ocean protects the test site from the eyes of prying and external intervention.<br>
Question: What made the test bar for the plane?<br>
Answer A: Moutant bottom<br>
Answer B: Lake top<br>
Answer C: Lake bottom<br>
Answer D: Lake right<br>
**True answer:** C. Lake bottom<br>

# File structure
QuestionAnswering_MultipleChoice_BERT/

├── Demo.ipynb

└── README.md

# Dependencies, basic commands and libraries
List of dependencies, basic commands and libraries required to run the .ipynb file.
pipeline: Deploy the model
SentenceTransformer: Encodes text sentences into numeric vectors of height
cosine_similarity: Calculate the similarity between two texts
gradio: Create interactive user interfaces for the model

# Contribute
If you want to contribute to our project, follow these steps:

- Fork the project.
- Create a new branch on your fork.
- Make your changes on the new branch.
- Create a pull request to merge your changes into the main repository.

# Author 
This project was created by ShynBui.
