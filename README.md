# SWP-AD
# Digital Lecture Helper (DLH)
Sometimes, note-taking can be hindering in classes. Some students write very slowly, and therefore have a more difficult time keeping up. Other students get caught up on deciding what they should or should not be writing down, so they cannot focus on participating or listening. Because of these reasons and more, some students tend to record the class lectures. However, they find it difficult to organize the main contents by listening to the recordings again. 
Furthermore, students who study abroad often feel a great burden on understanding the classes conducted in different languages.
Taking the above difficulties in consideration, we thought of making a desktop application which comes with features such as:

-Real-Time Speech Recognition<br/>
-Saving Audio Files<br/>
-Text Editing<br/>
-Real-Time Translation<br/>
-Showing Recognized/Translated Text on GUI and Saving Its Text File<br/>

![image](https://user-images.githubusercontent.com/54922683/116508930-59b29480-a8fd-11eb-933a-83e052f7f91b.png)

### Program Specification
**Program Type**: Desktop Applications<br/>
**program specification**: pyqt5<br/>
**Back-end language used**: Python 2.7 and above<br/>
**Internet connection required**: required because it uses the client-server API<br/>
**Supported OS**: Linux, Windows, Mac OS<br/>
**Key APIs and Libraries used**:<br/>
**Google cloud speech API** - uses a powerful neural network model with an easy-to-use API, enables developers to convert audio into text. This API supports the global user base by recognizing more than 120 languages and dialects.It can be used to  implement voice commands and controls, to convert audio from call center to text, and use Google's Machine Learning technology to handle real-time streaming or pre-recorded audio.<br/>
**Google cloud translation API** - can dynamically translate text between thousands of language combinations. It allows users to integrate websites and programs with translation services in a programmatic manner.<br/>
***Json file and Google Cloud SDK folder** - the former is required for credentials and the latter is required for importing the appropriate python modules in the source code<br/>
**Virtual Environment**: Virtual environment was used to install all the required modules and eventually run the program. The commands made on linux terminal include:<br/>
“virtualenv takeClass”<br/>
“source takeClass/bin/activate”<br/>

#### Example of Use
[![Video Label](https://youtu.be/5yELvVQvrgQ)



