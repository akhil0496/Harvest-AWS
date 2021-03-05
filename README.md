# Harvest-AWS

####steps:####

Step1: Do ```preprocessing``` and ```model building``` with raw data

Step2: Save our trained model to the disk using the pickle library. 

###Pickle### 
Is used to serializing and de-serializing a Python object structure. In which python object is converted into the byte stream. dump() method dumps the object into the file specified in the arguments.

Step3: Sign-in to AWS account. Create a instance. 

Step4: Use putty generator and give access to instance

Step5: By winscp do file transefering

###WinSCP### 
Is an open source free SFTP client, FTP client, WebDAV client, S3 client and SCP client for Windows. Its main function is file transfer between a local and a remote computer. Beyond this, WinSCP offers scripting and basic file manager functionality.

Step6: Add security network to the instance 

Step7: Run python file in our terminal

Once we give our values it gives prediction

for ex: for ```fertilizer prediction```

![image](https://user-images.githubusercontent.com/50659114/110110931-8ce11780-7dd5-11eb-8075-d74be5a095cc.png)

for ```crop prediction```

![image](https://user-images.githubusercontent.com/50659114/110111178-ef3a1800-7dd5-11eb-83a6-092caceeabe6.png)



