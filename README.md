# Suns Out Hacks Out | Major League Hacking

<img src="data/banner.png">

# Moodector 
A simple web app that uses ML to detect the mood of a user.
![Glimpse](https://github.com/AshishJGalagali/Moodector/blob/master/data/Moodector!.png)

## General Information
The COVID-19 pandemic has resulted in over 1 billion students worldwide facing school closures. As schools continue adjusting to remote learning, we must address the novel challenges that online learning presents. One such challenge is the inability of instructors to determine how well students are engaging with the lecture. Unlike physical lectures where the instructor presents to a live audience, web conferences makes it difficult for the instructor to monitor the reactions of all the students. As summer ends and the fall term begins, this problem becomes even more pressing.

In order to address this problem, we came up with the idea of using ML to classify the emotional state of students in a virtual classroom. Using Azure Cognitive Services Custom Vision. The facial expressions can be categorized in 5 ways: confused, bored, excited, happy, tired. For now the demo consists of only 2 classes, i.e. interested and confused. This would allow instructors to understand how their lesson is being perceived and get a better idea of how to shape the class to meet students’ needs. 

## Usage 
The web application demonstrates how mood classification works for students during an online class. The user can enter an image url of a photo with faces of the participants and press the analyze button. The image submitted by the user will subsequently be shown in the bottom left and the resulting classification and confidence percentage will be displayed on the bottom right.

## Future Extensions
One potential extension to this project is to have a continuous analysis of a student's emotional state. Students’ response to the lecture changes throughout the lecture and a real-time analysis would be much more informative to the instructor than a single snapshot. However, we would need to be aware of how much analysis is acceptable and make sure that this feature does not invade the students’ privacy. The data could be anonymized so that their privacy is protected and the instructor can still see the points during the lecture when students are confused. Additionally, we could extend this project by providing a greater range of emotional states and more accurate results.

## Team
[Vedant Bahel](https://github.com/vedantbahel), [Marcus Christerson](https://github.com/marcusch), [Ashish Galagali](https://github.com/AshishJGalagali), [Priyanshu Agarwal](https://github.com/priyanshuone6), [Melissa Mitchell](https://github.com/MCMitchell8) 


