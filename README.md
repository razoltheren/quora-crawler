# quora-crawler
To get question links:

1) put topic name and urls in topic_names.txt and topic_urls.txt similar to current format
2) run the main python function with argument : getquestionlinks
3) After this you will see question local links in questions.txt

To get all questions in answers.csv:

1) delete answers.csv because program needs to create it itself
2) questions_done.txt contains questions that data for them is stored so far.
    if you wanna start all over again, delete content of this file.
3) run the main python function with argument : downloadquestions


To restart eveything:

1) delete answers.csv because program needs to create it itself
2) questions_done.txt contains questions that data for them is stored so far.
if you wanna start all over again, delete content of this file.
