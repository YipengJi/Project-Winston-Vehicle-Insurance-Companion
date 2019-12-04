# Winston
- created at Hack the 6th, 2019 by Penny Ji, Andrew Mourcos and Robert Toyonaga.

Winston is an Android application that assists users after they have been in a car crash. Winston collects data, and 
compiles a report that will help in the insurance claim process. Winston uses tensorflow-lite to classify types of car 
damage in real time on the user's phone. This can all be done locally, without internet access.

<a href="url"><img src=Data/images/winston.jpg align="left" height="400" width="200" ></a>

<a href="url"><img src="https://raw.githubusercontent.com/andrewmourcos/Winston/master/Data/images/2019_08_25_06.40.11.jpg?token=AIOBZ25VNPDANUPG7N6FZGK5NOSAC" align="left" height="400" width="200" ></a>

<a href="url"><img src="https://raw.githubusercontent.com/andrewmourcos/Winston/master/Data/images/2019_08_25_06.39.43.jpg?token=AIOBZ25JAVBHYR3VYR77MAK5NOQYI" align="left" height="400" width="200" ></a>

<a href="url"><img src="https://raw.githubusercontent.com/andrewmourcos/Winston/master/Data/images/2019_08_25_06.39.09.jpg?token=AIOBZ233WBUMMJTC2OG5IO25NOQVK" align="left" height="400" width="200" ></a>

### Inspiration

During our research, we found that a lot of people face difficulties in claiming their motor damage in a timely manner. It would be beneficial to have a system for the customer to make claims faster and for insurance providers to set aside the claim cost accurately. Thus, we decided to create an app where the customer can submit claims and receive an estimate repair cost by simply take a picture of the damage. To avoid panics after an accident, we also provide instruction for after-accident care. We want to help facilitate a more efficient claim process system.

### What it does

Our AI-based app can instruct the customer what to do after an accident happens, identify the motor damage parts and severity with our well-trained ML model, provide an estimate repair and claim cost and send a complete report to the insurance provider.

### How I built it

We used both TensorFlow and TensorFlow Lite to train on thousands of collision images we scraped from the internet. We classified them accurately and trained the model to identify them. Then we integrate the trained model into an Android app with Android Studio.

