# genshin-login-helper-actions

Auto Daily Checkin For Genshin Impact

How to use:
<br />
<br />
<br />
1. Fork this repo

2. Getting Cookie
   2.1 Go to the Daily Check-In event website https://act.hoyolab.com/ys/event/signin-sea-v3/index.htmlact_id=e202102251931481&mhy_auth_required=true&mhy_presentation_style=fullscreen
   
   2.2 Log in with your MiHoYo/Genshin Impact account.
       If you have never checked in before, manually check in once to ensure that your cookies are set properly.
       
   2.3 Open the developer tools on your web browser (F12 on firefox/chrome)
   
   2.4 Click on the “Console” tab
   
   2.5 Type in document.cookie in the console
   
   2.6 Copy the text output from the console and save it somewhere e.g. notepad etc.

   ![image](https://github.com/Dekerz12/genshin-login-helper-actions/assets/124056161/c37531ca-e6f4-44cd-bb84-a5fc1be1a512)
   
   2.7 Get user agent and copy the text output too
   
   ![image](https://github.com/Dekerz12/genshin-login-helper-actions/assets/124056161/b78361fb-4435-4156-b468-c0c4fbd5aae0)

    
3. Go to the settings > security > secrets and variables > actions

4. Create New Repository Secret then paste the cookie under OS_COOKIE and the user agent under USER_AGENT
   ![image](https://github.com/Dekerz12/genshin-login-helper-actions/assets/124056161/9f43550c-6864-4cec-9cf6-bda538e53f83)
   
5. Profit!!!

Credits to: 
https://github.com/am-steph
<br />
https://am-steph.github.io/wayscript-login-helper/wayscriptx

