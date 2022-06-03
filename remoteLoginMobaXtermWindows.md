## How to: Remote login using MobaXterm (Windows)

#### Step 1:  
If you haven’t installed MobaXterm, please follow the [How to: install MobaXterm](installMobaXTermWindows.md) to install this program on your computer.  You will need an account to access the remote server (**storm.cis.fordham.edu** for RH classes, **erdos.dsm.fordham.edu** for LC classes). Please speak with your instructor if you don’t have one, or have forgotten your account ID or password.   
  
In the following examples, I be using my account information, "cking74@storm.cis.fordham.edu" and the password “mypass”. Remember that when you see this, you should replace it with your own details. 

  
#### Step 2:  
First ensure that you are connected to the internet, then double click on the MobaXterm icon to start the program. The following window will appear:  
  
![Opening screen](docs/assets/CISWork11.png) 
  
  
#### Step 3:   
Click on the Session button on the top left of the window:  
  
![Session button](docs/assets/CISWork12.png)
  
   
#### Step 4:  
(In the new window), first click the **SSH** button (top left), then in the **Remote Host** text box, enter the host name of the remote server to which you want to connect. (In the example shown, I enter **storm.cis.fordham.edu** since my account is located on the storm server.)   
Next, check the **Specify username** box and enter your username. (Here I enter mine, cking74.) Click **ok**.  
  
![Enter login](docs/assets/CISWork13.png)
  
  
#### Step 5:  
If successful in the previous step, a terminal window will appear as shown below. You should see your username and a password prompt. Type your password –“mypass” and press **Enter**. (Note that as you type your password, the cursor will not move forward and nothing will be shown for security reasons.)  
  
![Enter password](docs/assets/CISWork14.png)  
  
  
A window may pop up asking if you wish to save your password. Only do so if you are on your own private computer. _If you are using any public computer, click on No._  
  
![Save password option](docs/assets/CISWork15.png)  
  
  
#### Step 6: 
After successfully logging on, you should see something similar to: [cking74@storm~]$ appear behind the cursor in the terminal window (with your own account information) as shown below. This indicates that you are currently accessing the server.  
  
![Accessed server](docs/assets/CISWork16.png)  
  
If you want to log off of the server, you can type exit into the terminal window and press **Enter**.

**Congratulations!** You now know how to log on to a server using MobaXterm! 
