# Joystick-

Our application is an Android app Remote Control Joystick.
In the application we connect to a flight simulator (FlightGeer) by ip (of the computer that the fligtGeer runs) and port of the fligtGeer.
After the connection we can start the fly and control at the flying of the airplain by the joystick and the two sliders - throttle 
and rudder.
In our aplicattion we use MVVM architecture. 

In this [link](https://youtu.be/qwIGTnreLnA) you can see a video that explains a bit about this architecture in our project, 
the structure of the application and a demo of the application.

## Instructions:
1. First, you need to download fligtGeer at this [link](https://www.flightgear.org/)
2. Then, you need to download Android Studio IDE at this [link](https://developer.android.com/studio)
3. Now, open the flightGeer and go to Setting->Additional Settings and type this command:
   * --telnet=socket,in,10,127.0.0.1,6400,tcp
4. Download the files as zip files, and then extract them
4. Now, open the files in Android Studio : click on File -> Open -> the folder(Joystick) -> ok
6. In the flightGeer you need to press on 'fly' and then press on 'v' in your keyboard
7. Run the project in Android Studio
6. When the application's screen opens, enter the ip and port (6400), and then click on connect

Enjoy!!!

### The UML:

![image](https://gm1.ggpht.com/0tB6FrKjNHNRxwca_UUvcvQQLMqr1E0Z71Kqt2xjXpSut3ekWDx14uMw6NTINJdqsT8U4RZHW6xznKLtcKOt5MZBnDgAFgPzTq9jsURR8JG6eOqBBS6OMHPlCh91SUiXR2xS6pH1EOROeYeXjEcXNPvZrgVyuyWc3Oyyaq919eAxdTinmwOk65dxSZyZkDg2bInhOwZEYhnoWUG7NrShCR5iMU_GPf3jTAj9Skaufk0eL5z6NUw0xZd1fMLNgjE88SICr6lfh532lQqVMz5okUny6BSNnhojCczjQQXOFpO4ukzrFLT6GjehwgjBsEHE7yf7hE9m8YcgrJm_sl2uqetRDzo5lVss7x4iBui8hP541K9OSoZfDVSmmcF76B2MYTBGDKp5c8y0HukCrLPzHlo6nrBg9ds-DHwObM3JnVSQu85pARNn-oVZzEdDpgdcB_5aKA_fWxZnDPV9BHgSh8TmdGuO_mcfTL8glR3BcN_2RykiqtQ1riWHqq1eEmXHqw2Ml0g2WDARvHk0o7Bi65nsIquJ3PmfhYxKqFL93c73tpPg1cPMtHXR0nuIWiC3MgVS_RgjjNjsVsL1lsSdcXgA8Ou97gfqQehHzd7Kh6Q-eBvAFYKuYrX53AL9GI5ghem1MPxaS0pJND1JD-FS5_dNmjCa77M3T1kZ8Ambve-UIrXa3jfnhzIHAEu0maarCq3crcWmAdwMj2HGPlmoybo8yPmwwbVEiXhKtU3GAY57mstAnmP57qiJL6LiU_DJD3U=s0-l75-ft-l75-ft)

