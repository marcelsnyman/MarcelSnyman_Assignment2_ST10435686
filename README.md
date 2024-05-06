HOW TO PLAY
-
STEP 1: Open the application

Step 2: Press on the Play button at the bottom of the screen as displayed in the image below!

Step 3: You can now Feed, Clean or Play with Oreo by pressing on the respective buttons! Be sure to look after him!
![image](https://github.com/marcelsnyman/Assignment2_ST10435686/assets/164025078/fcd1c440-1179-4ed6-a5bc-c31c78928537)
![image](https://github.com/marcelsnyman/Assignment2_ST10435686/assets/164025078/a249c6de-5617-402d-94e4-9dc25b38c528)

Report Introduction
-
I was asked to create an aplication that is a replica of a tamagotchi virtual pet. In my application you can look after a cat named Oreo. You can feed him, play video games with him and clean him while keeping a close eye on his statistics (health, hygiene
and happiness)

GUI Design
-
Before designing my application, I wanted to make sure that it was easy and straightforward to use. I did not over complicate any tasks and made it easily understandable for all ages.
I tried to keep a consistent colour scheme, as well as a consistent "bright" theme. I went with easy contrasting colours with the buttons so that they could stand out easily from the
background and be easy to read. I added labels and big text to make it easy to read and straight forward to understand. Below are screenshots from my applications user interface.

 
![image](https://github.com/marcelsnyman/Assignment2_ST10435686/assets/164025078/e3eabb43-05bd-4ac0-bd68-3139cc7e9ec1)
![image](https://github.com/marcelsnyman/Assignment2_ST10435686/assets/164025078/25aa94bf-7107-4b3d-896c-221e8d8f55cd)
![image](https://github.com/marcelsnyman/Assignment2_ST10435686/assets/164025078/5cd7025d-1b24-4487-a195-46e50fed961e)
![image](https://github.com/marcelsnyman/Assignment2_ST10435686/assets/164025078/7c063cd5-8961-42bc-917c-a401bb6f6027)

I had decided to stick with the soft pastel colours for the backgrounds / statistical colour indicators as it contrasted very well with the dark brown colour of the buttons.
As brown is also not a usual colour used for these typical details, I believe it makes my application look much more unique. It also matches well with the cat Oreo (originally named Pusheen).

Code
-
As my program was very simple, the code required to make it work was not complex and easy to understand. The image below was the code I used to switch to the 2nd activity of my
application.

![image](https://github.com/marcelsnyman/Assignment2_ST10435686/assets/164025078/4276581a-a4cf-427e-8042-bda443bc6e3d)

The code below is a representation of what will happen when the "Feed" button is pressed, however the code is very similar to the other 2 buttons as they fundamentally work the same.
The highest value is 3, while the lowest value is 0, Therefore when the button is pressed, it sets the hunger variable to the highest value it can be (which is 3). While this is happening,
it decreases the values of the other 2 statistics that are not increasing by 1. After this has been done, There are multiple checks being done to see what the value is. The checks are done to then
represent the corresponding colour to the TextView background. There is also a check done to see whether a value has hit 0. If it has done so, then it wont decrease any further after reaching 0. Once
all the necessary checks have been made, it then proceeds to output the new values and colours into the respective TextView objects.

![image](https://github.com/marcelsnyman/Assignment2_ST10435686/assets/164025078/a42015ac-b716-41fa-8542-6273bc8f662f)


GitHub
-
I created a repository on GitHub to upload my program and to help keep progress of my workflow. I used it to regularly commit any changes 
I make to my program and If I ever make a big mistake, I can recover a previous state of my program at any time. I have also added a unit test
file within my folder to properly test my application.

