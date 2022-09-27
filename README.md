# Audio_Classification
Classification of Audio using Machine Learning Techniques.

<h2>Basic Problem/Solution</h2>

Here we try to find a machine learning model to correctly predict the song lable where the population of data contains data points belonging to 2 song labels, making it a binary classification machine learning problem.

<h2>Advanced Problem/Solution</h2>

Here we try to find a machine learning model to correctly predict the gender of the person who hums a song. If we can identify the gender of a person by analysing hums , this can be applied in gender based voice recognition tasks.

Usually , the male and femal voice is differentiated by the human structure of the male and female vocal cords (https://simple.wikipedia.org/wiki/Vocal_cords). In general female voice has a higher pitch compared to male voice. Therefore for this task we explicitly use only hums, because for humming human vocal cords are generally used while for whistling in general the human vocal cords are not used.

In the meta data of the MLEnd Hums and Whistles data set we have the gender recorded for the IDs. Out of the 275 IDs, we have the gender recorded for 187 IDs (68% of the total IDs). Since it is a resonable amount of IDs we planned to extract the hum audio recordings relevant to those IDs where the gender has been recorded in order to train the machine learning models.
