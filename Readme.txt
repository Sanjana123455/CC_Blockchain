1. There are two sides in our project client side and server side. So we need to run client side in Command Prompt and server side in PyCharm 2021.1.1 software

2. Simple way to have PyCharm is to download Anaconda Navigator(anaconda 3), where almost many python related apps will be there in the Anaconda Navigator app homescreen.

3. To download the Anaconda Navigator, in your web browser just google Anaconda Navigator Free Download, then open the first link you get, the official website of anaconda, that is, https://www.anaconda.com > products > individual. The download option Anaconda Individual Edition for windows will be visible, click that if your operating system is windows and then anaconda navigator will get downloaded. After it gets downloaded, open it from downloads and complete the installation setup.

4. After the Anaconda Navigator app is installed completely, open the Anaconda Navigator(anaconda 3) app which will have green round ring icon, and when you open the app, in the home screen of the app there will be ,any python relted apps including PyCharm. We need PyCharm, There you have the option to install and launch the app, so click on it, install and then on launch button of the Pycharm Professional 2021.1.1 app. Now finally PyCharm app will be available in your windows search bar in the main lockscreen of your device.

5. We also need Python 3.6 software to be installed for our project. So in your eb browser google Python 3.6 free download, then open the first link you get that, that is, https://www.python.org › downloads › python-360. Open this link and at the bottom of the page when the page is dragged completely, you find all the versions listed under the bold heading Files, Then select this option and download it if your operating system is windows, Windows x86-64 executable installer. After the app is downloaded open it from downloads and compete the installation setup.

6. Save the Project Code folder named CC_Blockchain in the Local Disk(D) path of ur pc. 

7. Now open the PyCharm app, then from File option click Open option and then choose the Local Disk(D) project code folder CC_Blockchain in PyCharm. Then in Pycharm we need to run the server sude of our project named with file "blockchain". 

8. Now select the run option tab present above in the app, and then select Edit Configurations in run, now here there is a option Python interpreter in the Configuration Logs section. Now select the Python interpreter by choosing the path where you have downloaded as "Python 3.6" which we have got installed. Then there is also Working directory option, below the Interpreter options. So choose the server side file path you want to run in Pycharm that is, CC_Blockchain > part1_crypt_blockchain > blockchain. So the working Directory will be,
 D:\part1_crypt_blockchain\blockchain

Now above in the Configuration Logs section, there is a option called as Script path. So choose the scrypt path of the file you want to run that is the server side of project which have been named as, part1_crypt_blockchain > blockchain> blockchain.py, which is saved in Local Disk(D). So the Script will be,
 D:\part1_crypt_blockchain\blockchain\blockchain.py

9. Then select the ok option below, after the Script path, Python interpreter and Working directory is choosen.

10. Now install all the necessary packages needed for the project.
    (Note: Uninstall the anacona navigator app, after you are confirmed that PyCharm is successfully installed, because anaconda            Navigator app will block some python packages from getting installed)

11. There are two ways of installing the packages: 
1) select the File option in the PyCharm Software, and then select settings. In seeings you have a option called as "Python Interpretor" under the option Project:pythonProject. So select the Python Interpretor option and then above choose the python interpretor as Python 3.6 which you have got installed and then there is a "+" (plus) option above the packages installed, on which when you press, you can search for the package you want to get installed and then press on option install package and get it installed.

2)In the windows search bar, by typing cmd open Command Prompt and then give the command, 
pip install "package name you want to install"
Eg: If you want to download the package rsa: 
    pip install rsa

Try the first Pycharm Project Python Interpretor method to install the packages, if you cant any of the find the package there, then try to install the package by command prompt pip install method. So you can install aome of the packages by first PyCharm method and some of the packages by second cmd method. Fist pycharm method i prefer rather than pip cmd method.

12. So the packages you need to install are: cryptodrome(pycryptodrome), pycryptodomex, pycrypt, crypto, rsa, urllib3, pyparsing, pycparser, Flask, Flask-Bcrypt, Flask-Cors, jsonify, requests, render.

13. When the above mentioned packages are installed, we are ready to run the project code. Run the server side file part1_crypt_blockchain named as "blockchain.py" file in PyCharm. So for this, click Run option in the above tabs of PyCharm app, and then again press Run option in Run tab, then click on blockchain file. Now the server side file named "blockchain" gets run in PyCharm, now after you run you will get a link in Pycharm output, 
 http://127.0.0.1:5000/
Copy the link you obtain and paste it in seperate google chrome web browser. So your server side of project is ready.

14. Now to run client side of the project, in the window search bar, search for cmd, open the Command Prompt and give the following 7 commands as mentioned below one by one giving the enter button:
    1) cd..
    2) cd..
    3) D:
    4) cd CC_Blockchain
    5) cd blockchain_client
    6) cd blockchain_client
    7) blockchain_client.py

when the following commands are given, after the 7th command when you give enter you will be provided with a link like,
http://127.0.0.1:8080/

copy paste the obtained link in a google chrome seperate web browser. Now you are ready with Client side of the project.

15. Now when you have opened both the client side and server side links obtained, in seperate browsers. Remember that the client side file is named with the Blockchain Client tab and server side file is named with Blockchain Frontend tab. Now open the Blockchain Frontend tab, there in the right corner you can find Mine and Configure options. Press on Configure option, and then a node url with a empty textbar space will appear, then give in the node url text bar as:
 127.0.0.1:5000/
then after giving that node url, press Add Node option that you can see below right there. Now you can see 5000/ gets added below that you can see in blue colour. Then add another Node url in the textbar, this time by giving:
 127.0.0.1:5001/ 
Then press Add Node option. Now 5001/ gets added.

16. Now after adding notes, open the client side tab that is, Blockchain Client tab, Now you can see Generate Wallet option. When you press that option, a public key address and private key address wil be genearated, copy the public key address and private key address and you have to press on Generate Wallet again and the public id generated for this time will be change from previous public id address, this second time generated public id address is taken as Recipient Address and store and save all the 3 in in notepad. You can see the three options in Blockchain Client tab: Wallet Generator, Make Transactions and View Transactions. Now press on Make Transaction option and copy paste the public id in Sender Address and private id in Sender Private Key and Recipient Address.

I have already saved and stored the Public id, Private id and recipient address in notepad that i will provide below. So instead of following above said step 16, you can directly copy paste the address i have mentioned below in Sender Address, Sender Private Key and Recipient Address:

Public key(Sender Address):

30819f300d06092a864886f70d010101050003818d0030818902818100f48912ca70c53c29115dd333afbc4e7881e40af6dda6189c9595e6c5d485d733a89914158e5974f124bb3ae2f61be9d61e921c818d2da16673610acf464262daa555de96af578a68f2b3bb24b75cbcbd024580a8ce299a4ef4777834ed3eb01524a1968983e93daf71be2e60100610c2c7136e1479cf086a3ee730fb51fcfee30203010001


Private key(Sender Private Key) :

3082025d02010002818100f48912ca70c53c29115dd333afbc4e7881e40af6dda6189c9595e6c5d485d733a89914158e5974f124bb3ae2f61be9d61e921c818d2da16673610acf464262daa555de96af578a68f2b3bb24b75cbcbd024580a8ce299a4ef4777834ed3eb01524a1968983e93daf71be2e60100610c2c7136e1479cf086a3ee730fb51fcfee3020301000102818061111a36e69dbc3c370b0ddf99f5ff1621c5423eed0bd6002df69364daf007d5172b30883ff9ad8c5d3ebee8c1b5a1d41f4d73684f8099ed3f8679527ebab25efe8c28625dd0a816bd8f5cc53a0855bd97e0941ff6a897f2984dca27e902880103798979aa9d38cade5d0bbb95bac5eb16b0ca4e21491b7c03c4867ae9dde6f5024100f4b9b7812278f26c1fde5d19f4fd61b10c23be04c0d3ff0ce58ed83ff49d4f5274aa69438561e2a932a1de16eff403343176bb2d8b2a8fcc9ad318ea1cff5bbd024100ffcd1d967381454c285544a5b65b3e9695f3d2f60e75e98ef0ddc41c0bff54e325a2821cdabe8736887bc31ffb58b7a2725d3130291e47fb65388956bb991f1f024100b66701f6370a6cadd866f57f96519111d41983d4a920999634376ec8e47aa797aeab214019576708735ba05bfa4726682d81f06b36b1e77239e7a347438bb505024004eeffd31707373ef0c8343abdf9a48b62f900e89dfec8326992dd656d15cf9d51ec8075ee021eb97e88648b095dfcacb567f6bae7101e734ad07c559fe8a4210241008e3e42d49dd2f1e85211648dc68ecbf0951288aea208d9bcc40b3f013863b3d26c6b3291e526a425071b7f78a6718d489cfb984a139a1ea1d3109327791ba697


Recipient adress:

30819f300d06092a864886f70d010101050003818d0030818902818100bb8973eefabc237f6cb480c501fbecb5f0e6a79975aa8fc3f116ea949848c4d871e400a2dfdf15cf96eb6faff0f98fa6d1886534028635d7d9becf70874384beddec800cb2529cc3f6fc3aa8aa1a27caa909cfde66c3cd74981ffce2fe84d1db13793eaa0502b16c2c5d9138d69506bb2161c1e871dc1aa88500e92097470c1b0203010001


copy paste the above things under Make Transactions, send coins in Sender Address, Sender Private Key and Recipient address respectively like u can see in the Result Fig. 4 in the Project Report. Now enter the Amount to Send like 1000 and then press on Generate Transaction and then on Confirm Transaction, A message Transaction Successful! will appear on screen. Similarly repeat one more transaction of amount of your choice like 300, by clicking on Make Transaction option in Blockchain Client tab and then copy pasting the Sender Address, Sender Private Key and Recipient address and then Generating another transaction of Rs. 300 and similarly you can Generate Transactions as many you want by following the same method. (Note: Somtimes it might take time for large amounts if the computer is lagging, so we need to wait a little for transaction successful message to appear)

17. After the transaction is successful, open client side tab that is, Blockchain Frontend tab and press on mine option and then press on "reload" button of "Transactions to be added to the next block" option. Then the transaction data will appear. 

18. Now press on "Mine" option which is highlighted as blue textbar in the centre of the page. Now press the "reload" button of "Transactions on the Blockchain" now you will see that the transaction is added forming blockchain.

19. Each time after transaction follow step 17 and 18.


                                    To deploy the web app in cloud platform- AWS:

1. We are goin to host the server siide of project using AWS and client side in Command Prompt(CMD). In the web browser, google out,
aws.amazon.com
You need to create an AWS free account, for this you will need a debit card. You will be cut with Rupee 1 for verification, then later you will be refunded with even this. 

2. After creating the AWS account open the link in sepearte web browser
aws.amazon.com
My "AWS account" username and password for sign in purpose:

Username: sanjanahegde234@gmail.com
Password: Sanju311

Then press on Sign in to cosole option that is on right corner. 

3. Then select Launch a virtual machine with EC2 option.

4. Then select the option which appears at 1st AMI in the top, that is,
Amazon Linux 2 AMI (HVM), SSD Volume Type - ami-0277b52859bac6f4b (64-bit x86) / ami-08814ae27e6f9262d (64-bit Arm)
Press on the select option of the above mentioned AMI.

5. Then Choose an instant type will be displayed, by default t2.micro will be choosen, without making changes leave as it is and click on Review and Launch option.

6. Then Review Instance Launch will be displayed on screen, drag the page below and you can see "Security Group" heading there, press on "edit security groups" option given on right corner of security groups. Then press on "Add Rule". then add HTTP and then press again on add rule and add RDP. Then change the source of all the 3 added security groups of SSH, HTTP and RDP to "Anywhere" from custom. Then press on Review and Launch.

7. Then Review Instance Launch heading appears on screen, now press on Launch which is at right corner bottom of the page.

8. Then a message with Select an existing key pair or create a new key pair appears on the screen, change the option from Select an existing key pair to Create a new key pair and randomly give some key pair name like, 
public_key22
Then press on the option, "Download key pair". Then press on "Launch Instances" option.

9. Then Launch Status heading will appear, then drag the page and in bottom you will find "View Instances" option. Click on it.
Then the public_key22 instance will be running. Then click on the Instance ID of public_key22 like, i-0458071882e7e4823. Then click on "Connect" option which is on right corner and then again press on "Connect" now you will be directed to amazon linux to AMI. Here we have to give some commands in this page.

10. Now here we have to give the commands as follows:

    1) sudo bash
    2) yum install python-pip
then press y when yes or no option is asked

    3) yum install git
then press y when yes or no option is asked
    
    4) pip install flask
    5) git clone https://github.com/Sanjana123455/CC_Blockchain.git
    6) ls
    7) cd CC_Blockchain
    8) cd part1_crypt_blockchain
    9) cd blockchain
   10) pip install -U flask-cors
       (to come out of the flask corse error)
   11) python blockchain.py
   
Then after these commands you will get a message like, Running on http://0.0.0.0:80/
At the bottom of this page you will get a public ip like,
Public IPs: 3.136.83.40

Copy paste this public ip 3.136.83.40 in seperate web browser in google chrome, so server side of project will be hosted in AWS.

11. To host the client side of the project you must store and save the project source code folder CC_Blockchain in Local disK(D).
Now to run client side of the project, follow the same steps from "step 14 to step 19" as given above, while running the web app in the normal localhost using pycharm. But here while hosting the web app in AWS you dont need the PyCharm app just having an AWS free account would be enough.












 





















 