# faceRecog_automation

Project Description 📄
❄️ Created a program that perform below mentioned task upon recognizing a particular face. 
📌 When it recognize your face then - 

👉 It send mail to your mail id by writing this is face of your_name. 

👉 Second it send whatsapp message to your friend, it can be anything. 


📌 When it recognizes second face.

👉 Create EC2 instance in the AWS using CLI. 

👉 Create 5 GB EBS volume and attach it to the instance.


Result:

![Alt text](https://github.com/shiv0112/faceRecog_automation/blob/main/images/shiv_face.gif?raw=true "Model Successfully Recognized the user's face with his name.")


On recognizing the user's face the code will send an email to the user's email address and a whatsApp message also.

![Alt text](https://github.com/shiv0112/faceRecog_automation/blob/main/images/whatsapp.png)
![Alt text](https://github.com/shiv0112/faceRecog_automation/blob/main/images/email.jpeg)

Then the code will run for second user, in this case Virat Kohli.
![Alt text](https://github.com/shiv0112/faceRecog_automation/blob/main/images/virat_face.gif)


After the code has successful run:

![Alt text](https://github.com/shiv0112/faceRecog_automation/blob/main/images/resulttt.png)

Finally an ec2 instance is created on AWS and a 5 GB EBS volume is also attached.

![Alt text](https://github.com/shiv0112/faceRecog_automation/blob/main/images/instance.jpeg)
![Alt text](https://github.com/shiv0112/faceRecog_automation/blob/main/images/volume.jpeg)

For demo please click the below link::
https://srivastavashiv0112.medium.com/a-face-recognition-program-for-security-and-automation-1aca2479a092


Your aws cli must be configured

Your email must have allowed access to less secure apps

Create a folder 'faces' with two subfolders


    'user1'
    
    
    'user2'
    
    
Replace the number in whatsapp() in main.iynb by your desired phone number.

First run face_model_creation.ipynb
Now run the main.ipynb






