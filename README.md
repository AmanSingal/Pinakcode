__*Covid-19 Fake News Detector*__

Fake news can be any content that is not truthful and is generated to convince its readers to believe in something that is not true. 
The challenge for fake news detection comes with the democratization of news sources, and how easy modern technology makes sharing news 
articles in the age of social media.


The Covid-19 Fake News Detector is a GUI that detects fake news, without compromising privacy, and is based on machine learning algorithms. 
When a user enters a message in the textbox provided on the interface, it accurately detects whether the news is fake or genuine based on 
the dataset of sorted messages from various official sources.

__In order to run the application on python:__

Main Code: fake_detect.py

Module : nlptrain.py

1. Run the code fake_detect.py on Python
2. Enter the input for news or message related to covid19
3. The console predicts the output prints 'Genuine' or 'Fake'


__Following are the code details for running on Webapp using Django:__

fake_predict: This is the base project folder for the DJANGO project app.

predict : This is an app for inside our project.
Inside this predict app we have written all our code for getting the text message from the user .passing the same into the function called fakepredict which is present inside fakepredict.py file.

templates folder contains a file called index.html which contains the  HTML code to take and display the result.

Once the user clicks on the submit button the data is sent to the url specified (i.e news).The specific url calls the views.py file isnide the predict app.

![image](https://user-images.githubusercontent.com/63463655/79018843-7238fb00-7b92-11ea-8ad1-7e6cd61856d7.png)






