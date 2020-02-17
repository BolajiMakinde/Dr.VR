# Dr.VR
In a relatively affluent society such as the majority of the United States, one would figure much of the population would take frequent steps to ensure their overall health given the financial ability. However, the contrary holds true. “The decline in the use of medical services was widespread, taking place regardless of health status,” said Brett O'Hara, chief of the Census Bureau's Health and Disability Statistics Branch. Even considering age differences, “Medical provider visits become more likely with age, as 37 percent of young adults 18 to 24 did not visit a provider at all during the year, compared with 8 percent of those 65 and older” (O'Hara).
Our research project, DR.VR, aims to solve this problem. The main inspiration to creating this project was the relationship of convenience and importance on the subject of health. There are countless ideas combatting a particular well-known condition or disease. However, one aspect of health often swept under the rug is basic regular health the general public are often too lazy to check up on. No one bothers to schedule a doctor’s appointment for a regular checkup because it is just “regular”. Unfortunately, many people do not feel financial health investments are worth the time unless it requires immediate attention. While regular checkups indeed aren’t urgent, they are crucial for providing the public with important warnings on their current lifestyles and any risks they are leaning towards; hence, DR.VR came to life. Our product allows patients to reproduce the benefits of a regular doctor’s appointment without the financial or time-demanding burdens. With virtual reality and machine learning analytics, we are able to produce a product that can positively affect many lives across the world.

DR.VR aims to simulate a real-life doctor’s office visit for the patient. From putting on the VR headset the patient is placed in a room very comparable to a typical doctor’s office. A desk can be seen along with a chair to sit on, with medical posters, objects, and diagrams throughout the room. A virtual doctor is present ready to introduce you to the Check-Up Exam. The evaluation is divided into 3 series of tests: the visual, audio and physical components. In each component there are 2-3 tests the patient goes through by interacting with the scene in the VR headset and responding using the controllers provided. On the screen the scene will shift from its current location to a particular area of the room where the test will begin. A verbal and textual prompt is given to instruct the patient on what task needs to be completed for the test. After all tests have been executed, a feedback diagnostic is given to the patient with results and analysis on various aspects of health, and recommendations on what course of action to take next. The tests taken by the patient are as follows:

Eye Test: the patient is placed “20 feet” (in perspective of the VR environment and camera perspective) from an eye chart. They will be asked to verbally indicate what letters they see and we use Google Cloud speech recognition to grade their indications. From this we can estimate the patient’s eye score.
Color Blindness Test: To test for color blindness, the patient is shown two colors of very similar shading, and is asked to press the button on the controller once a difference in shades can be seen by the patient. The time taken to recognize the difference will be used to calculate whether the patient may have color blindness.
Hearing Frequency Test: A frequency pitch audio source is played for the patient, which won’t be heard until a certain frequency has passed for each patient. When heard, the patient presses the button to stop the audio and the time taken to hear a sound is converted into an estimated frequency limit that the patient can hear. This is compared to the classical scale of human hearing (20 to 20,000 Hz) to judge the patient’s hearing ability. 
Hearing Volume Test: As explained by the heading, base sound is played to the patient with increasing volume until the patient can hear it. The goal is to test if the patient may need hearing aids by checking if the base volume heard is higher the average for a person of normal hearing.
Location Perception Test:  In an environment with no objects, just a dark area, a sound is played for the patient just once. Using VR technology we can “place” this sound in any 360 angle and radius from the patient. They are required to estimate where the sound came from, and their margin of error from the correct spot will determine their audio perception.
Balance Test: One of the many advantages to utilizing VR technology for medical testing purposes is it allows us to harvest coordinate data on each of the used components to determine the current posture of the patient, using the headset’s physical rotation, along with the alignment of the headset and controllers, the patient can be provided feedback on their posture  and how well-balanced they are when performing various tasks.
Parkinson’s Disease Test: A simple method of testing for the risks of Parkinson’s Disease is by checking the tremorring of one’s hand when doing menial tasks. We can monitor this by checking the coordinate change in controller movements and determining whether there is sufficient oscillation to deduce a cause for concern for the patient’s specified age. 
Physical Perception Test: To measure physical perception, the patient is tested by reacting to an object being “thrown” at them in Virtual Reality as well as having an object placed at a random location with the patient required to estimate how far that object is. These allow for measuring the patient’s depth perception and reaction time involving motor skills. 

The purpose of these tests were to acquire feasible forms of numerical data to serve as a comparison with real-world applications. For each test, there was a value obtained from performing the task that we could check the deviation from medically obtained averages for people of normal health. It was important to note in the diagnostic section that any evaluation determined is merely an approximation; it should serve as guidance for the patient to take initiative and make a doctor’s appointment if they find concerning results in any field, audio or visual. The core strength in DR.VR’s impactfulness is global scalability. The goal of our research project is to allow people all over the world to have access to tests that can help them make better decisions about their health and give them prescriptions comparable to those of the world’s top physicians.

For more about our project and a working prototype, please visit DoctorVR.ml.
