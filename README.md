Good day | howdy | howzit | and quack-quack for all my ducks out there :) 

This will most probably one of the best pages you will find for doing this type of thing withing a weekend - depending on you use, mkay ?

To make apps, it's quite easy! The following is for making apps with python and kivy (this is what I did): 
  - https://www.youtube.com/watch?v=l8Imtec4ReQ
  
Then you will most probably make a .apk (android package) file:
  - https://colab.research.google.com/drive/1b9gMzs6XAtxCtahxei4N0fWZk7xiPlVw?usp=sharing
  - I found the easiest way was to use the above link. It is using Google Colab with a virtual buildozer
  - Follow the steps | code cells. 
  - NOTE: TO MAKE AN .aab FILE - WHICH IS WHAT YOU NEED TO UPLOAD TO GOOGLE PLAY CONSOLE (MORE ON THAT LATER) - CHANGE '!buildozer -v android debug' in the code cell in Google Colab
   to 'buildozer -v android release'
  - Make sure to Google your errors/questions - that's what I did
 
Great! Now you have an .aab file. What the hell must you do with that ? Well, you need to sign it. After 12 minutes of frustrated struggling and skipping throuh YTube vidjeos,
I came across an nice one, but it takes to long and you just want to copy and paste :) :

  - Firstly you will need to make a key with android studio. I know, I know - just chill and download it. Follow the steps here:
  https://developer.android.com/studio/publish/app-signing
  
  - You will also need JAVA JDK: https://www.oracle.com/java/technologies/downloads/
  
  - IN CMD PROMPT: java -jar dist/aabresguard_0.1.8_r3.jar sign-aab --bundle=path\of\your\unsigned\.aab\file --output=path\of\your\SIGNED\.aab\file --storeFile=path\of\your\keystore --storePassword=keystorepassword --keyAlias=keyAlias --keyPassword=keyAlias

YAY! You've signed your .aab! Remember when I said we will talk a bit more on the .aab file that you will need to upload to Google Play Console? This is it:
  - You will need a developer account with Google Console: https://play.google.com/console/signup
  
  - You will be billed in US dollars (US$25), but I mean, you can publish apps with this, spice up your CV and grow your career :D
  
  - Follow these steps for all the boring admin stuff: https://appinventiv.com/blog/how-to-submit-app-to-google-play-store/

Now you wait ... 


I waited a WHOLE WEEK for my app to actually be publlished. I was so excited. You will get an email from IARC Content Ratings. This means that your app was rated and is now on the playstore
if it was approved and all that stuff. 

My app that I made with python and kivy and by following this method above can be checked out here:https://play.google.com/store/apps/details?id=org.ontheplussideicon.ontheplusside

It's a simple calculator app that I made to literally just get the experience of making and publishing an app. Also, MAINTAIN YOUR APP. Fix stuff, publish your updates.
Don't just publish and neglectish :)

I do hope this has been helpful as this would have been absolute gold if I found this when I struggled with this whole process. 

Have a lovely day, stay safe and spread love - not COVID.
