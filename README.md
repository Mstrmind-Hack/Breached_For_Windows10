# Breached-For-Windows10

![ezgif com-gif-maker(3)](https://user-images.githubusercontent.com/104036615/169438252-24950392-0597-405b-9e70-70076e8b5451.gif)

**UPDATED VERSION 2!**

**This tool will help you Discover if your E-mail Address or Username was involved in a data breach.**

**The tool will also show you the number of breaches (if any), the most recent breach (in terms of days/weeks/years), and some of the websites on which your E-mail/Username was breached (Keep in mind, other individuals might have the same username as you on sites you're not associated with).**

**NOTE: Linux users, I have a linux version of this tool in my repositories!**



_**NOTE: If you're a begginner who cares about your online security and want to run this tool, you will have to install Python with Pip on your Windows machine.**_  Amit Thinks, Does a great job at guiding you through the steps needed during the installation process https://youtu.be/dYfKJMPNMDw



**VIDEO DEMO OF VERSION 1 OF THE TOOL** https://youtu.be/m1qaRTNf-7Q

**Step 1)** Clone or download the zipped folder of the tool to your windows machine.

        >>git clone https://github.com/Mstrmind-Hack/Breached_For_Windows10.git
       
**Step 2)** open CMD and change directories to the Breached Directory.
        
        >>cd Breached

**Step 3)** Install the tool requirements. 

        >>pip install -r requirements.txt

**Step 4)** Visit: https://leak-lookup.com/account/register and create a free **username and password** to access your **FREE API KEY**.

**Step 5)** Log-in to leak-lookup.com and optain your free API key. (Only 10 Searches allowed per day! Read their documentation!)

**Step 6)** Open API_KEY.py in a text editor and insert your API key in _**line 4**_ Between the quotation marks _**""**_ and save the file (See image below).

![api](https://user-images.githubusercontent.com/104036615/167968288-63798af3-7796-47a1-a77c-4e22a78ea899.png)

**Step 7)** Run the tool with: 

         >>python3 Breached_Tool.py
         OR
         >>python Breached_Tool.py

**Step 8)** Follow the prompts! It's that easy!

| API | Key Needed?|
|-----|------|
|1) portal.spycloud.com|No|
|2) leak-lookup.com| Yes|
