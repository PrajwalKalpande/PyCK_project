# PyCK_project
## Alphabet Recognition using CNN
The program recognizes that written letter and also recommends movie or song name that start with the letter that we wrote in air by voice as well as text written
on a window(with random images (in case of movies) and genre related images (in case of songs) in the background)
### Code Requirements :
This code is in Python (version 3.6 or higher). If you have lower version of Python can upgrade using the pip package .

To install the required Packages and libraries, run this command in the project directory after cloning the repository.
Copy paste this and type in command prompt:
```pip install -r requirements.txt```

### Data Description :
The "Extended Hello World" of object recognition for machine learning and deep learning is the EMNIST dataset for handwritten letters recognition. It is an extended version of the MNIST dataset. We also used csv files containing data about movies and songs. Movies data is ***titles.csv*** while Song data is ***songs.csv***
### Model Training :
We have used CNN model for predicting the alphabets writtten on the screen. 
Our trained model achieved Test loss: 0.19 and Test accuracy: 0.937

### Code Execution :
1. Open the terminal( cmd or powershell ) in the project directory and use the command shown below
 ```jupyter notebook```
2. Jupyter notebook will open in the browser window. Now go inside **code** folder and open >alphabet_recognition.ipynb
3. Now Click on **Cell** in menu and then **Run All**
4. Tada you can now have some fun!

### Instructions :
> *To select an option in Start/Recommendations window **double click** on movie/song name and then press **'a'** on keyboard*
> 
> *To hear the movie/song name in Recommendations window press **'s'** on keyboard*
> 
> *To quit the window(Start/Recommendations) at any instance press **'q'** on keyboard*
> 
Note : After u press 's' the Recommendation windows will close.
- After you run the code, a window will appear with **Movies and Songs** written on it select any one of them as instructed above.
- Now you will see a Recommendations window in which you can select any moviename(out of 3) or songname(only 1) 
- If you selected a movie, name a tab will open on your browser showing the results of Google Search of the movie name
- If you selected a song, a tab will open on your browser which will lead to spotify website where you can play the song
- Press 'q' to end 
- You can now again Run the file and draw letter and repeat the above procedure
