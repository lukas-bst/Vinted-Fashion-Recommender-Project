# FashUp - Fashion Recommendation Project using Deep Learning

FashUp is an aggregated solution that allows the end-user to upload his/her favorite clothing item and to quickly find the most personalised second hand item.

## 1. About the Project

Inaccurate product descriptions, possibly incorrect categorizations and a lack of personalized product suggestions contribute to an unsatisfactory user experience in the secondhand market.

Fashup is a web app that is developed to solve these problems by making it easier and quicker to find the desired clothing item throughout several platforms (limited to vinted.com in the starting phase). By uploading a picture of a clothing item that represents the preferred style, the user will be shown the most similar items that are currently available on the respective platforms in a matter of seconds. This is made possible by the use of an AI-model that recognizes the type as well as the style of the uploaded clothing item and identifies matching pieces.

While improving the user experience in second hand online shopping, Fashup is supporting a sustainable approach to fashion as well.


### Technology

- [ReactJS](https://reactjs.org/)<br>
- [NodeJS](https://nodejs.org/en/)<br>
- [Python](https://www.python.org/)<br>
- [Flask](https://flask.palletsprojects.com/en/2.0.x/)<br> 
- [PyTorch](https://pytorch.org/)<br> 
- [Jina AI](https://jina.ai/)<br>


## 2. Getting Started

For installation, please follow the instructions below:

### GitHub repo

1. Clone GitHub repo
  ```
  https://github.com/lukas-bst/Vinted-Fashion-Recommender-Project.git
  ``` 

### Frontend: React App

2. Install React App dependencies inside the `1. Frontend` diretory by navigate via command line to the /1. Frontend directory and run the following commands:
  ```
  npm install
  
  npm install @mui/material @emotion/react @emotion/styled
  
  npm install axios
  ```

3. Start the local server environment 
  ```
  npm start
  ```
  
### Backend: AI Model

4. Install all dependecies via the requirements.txt file by navigating via command line to 0. Backend/requirements.txt root and run the following command. Be sure to run your environment on Python 3.9 or below:<br>
```
pip install -r requirements.txt
```
5. Manually open the 0. Backend/main.py file in your preferred IDE and replace the following paths with the paths to your own cloned directory:<br>
```
database_path = own_path/0. Backend/1. Database/*.jpeg
database_information = own_path/0. Backend/1. Database/database_information.json
target = own_path/0. Backend
```

6. Navigate via command line to 0. Backend/main.py root and execute the main.py via the following command:
```
!python main.py
```
Note: In case there might arise error warnings with the libraries torchvision, docarray, flask install the libraries via conda:
  - conda install torchvision -c pytorch
  - conda install -c conda-forge docarray
  - conda install -c anaconda flask

7. The infrastructure is now set. Now let us see how to use Fashup itself:

  Step 1: Upload a single picture with your favorite item<br>

  Step 2: Click an "Search" & suggest 4 most similiar items<br>

  Step 3: Research your favorized item & navigate to online shop<br>


## 3. Limitations and further outlook
1. **ENHANCE AI MODEL**: Train the AI model on the DeepFashion database to improve its accuracy and increase the variety of fashion items it can identify.
2. **COMPLEMENTARY FEATURE**:Provide complementary fashion items that can be suggested to users based on their preferences and previous searches.
3. **MOBILE APP**: Develop a mobile app for the platform to improve accessibility and user experience for mobile device users.
4. **USER MANAGEMENT**: Develop and implement user accounts for the platform to allow users to save their preferences, track their orders, and receive personalized recommendations.
5. **MULTIPLE PLATFORMS**: Enlarge the database by integrating other online marketplaces such as Depop, Vestiaire Collective, ThreadUp, etc., to offer users a wider variety of items to choose from.
6. **FASHUP ECOSYSTEM**: Integrate tailors, designers, and stationary retail shops into the platform's ecosystem to offer users personalized services such as tailoring, custom design, and personalized styling. This will also help small businesses to reach a wider audience and boost their sales.
7. **MAIN LIMITATION**: The current database was scraped at the beginning of 2022, so some of the pictures may not be displayed correctly in the frontend.

## 4. Further description of the files
- ```0. Backend```: Folder contains all files neccessary to setup FashUp's backend
- ```1. Frontend```: Folder contains all files neccessary to setup FashUp's frontend
- ```2. Project_Presentation > Fashup_Presentation_vFinal.pdf```: Project presentation which gives an overview of the problem and the solution
- ```3. Images_Frontend```: Folder contains sample pictures for our frontend
- ```4. UX_UI```: Folder contains background information about our UI/UX research 

## 5. Credits

We'd want to express our gratitude to the TechLabs staff as well as the numerous volunteers that made this adventure possible. Our Journey Leads, Track Leads, and Project Mentors deserve special gratitude for always being available to answer inquiries and solve problems. You've always been there for us, encouraging us, motivating us, and keeping us on our toes.

## 6. Team 

### Project Team

- UX Siraprapa Chalermphao
- WD Roman Wiegel
- WD Cem Akbulut
- AI Lukas Bauerschmidt
- AI Fabian Barulli

### Project Mentor

- Bogdan Ciobotaru

