# Lottie-Animation
 Animation using Lottie

Select an Animation
Go to https://lottiefiles.com/ and select any animation of your choice. For this example, I’m going to choose 3 different animations:-
https://lottiefiles.com/3269-thumbup,
https://lottiefiles.com/434-gradient-animated-background, and
https://lottiefiles.com/440-stop-go-radio-button
Download the animations and rename them.. For example, the ones used here were renamed to “thumb_up.json”, “gradient_bg.json” and “toggle_switch.json” respectively.
Fire up Android Studio
Create a new project.

![image](https://user-images.githubusercontent.com/20369800/75105614-902aba80-563b-11ea-9339-9253ae209406.png)

2. Select Empty Activity.
3. Name your application. In this example, I’ve decided to go with LottiePlayground. Please ensure that the “Use AndroidX artifacts” feature has been enabled. Click on Finish.
4. Once the project is completely loaded, go to app level Gradle file and under dependencies, add
implementation ‘com.airbnb.android:lottie:$lottieVersion’
At the time of writing the latest version of Lottie is ‘3.0.0-beta1’.
5. Sync the project Gradle files.
6. Create a folder “assets” under app > src > main and paste the downloaded animations in it.



![16406-colorfull-loader](https://user-images.githubusercontent.com/20369800/75105580-31654100-563b-11ea-903d-7d89c882bd1c.gif)
