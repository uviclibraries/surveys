---
layout: default
title: 1 - Creating Basic Multiple Choice Surveys
nav_order: 2
parent: Workshop Activities
customjs: http://code.jquery.com/jquery-1.4.2.min.js
---
# Activity 1 - Creating Basic Multiple-Choice Surveys

1.	For this activity, make sure to login in on SurveyMonkey using your UVic credentials using the link [here](https://www.uvic.ca/systems/support/web/surveymonkey/index.php){:target="_blank"}
    - Alternatively, you can use the [free version of SurveyMonkey](https://www.surveymonkey.com/){:target="_blank"} by using an email address. However, the free version may have some limitations whereas the UVic subscription is a complete one.
2. Once you are logged in you will see the following page and on the top right a box that reads **CREATE SURVEY**.
    <img src="images/act-1/sm-1-01.png" style="margin-left:10px;width:600px;" alt="create survey">
3.	Go to the left pane and click on **START FROM SCRATCH** as in the picture below:
    <img src="images/act-1/sm-1-02.png" style="margin-left:10px;width:200px;" alt="start from scratch">
4.	 The box below will pop up, name your survey as <code>ENVIRONMENTAL ATTITUDE SURVEY</code>, for category you can choose **OTHER** and click on **USE MY OWN CONTACTS**.
    <img src="images/act-1/sm-1-03.png" style="margin-left:10px;width:600px;" alt="name survey">

5.	Click on **CREATE A SURVEY**.
    <img src="images/act-1/sm-1-04.png" style="margin-left:10px;float:right; width:150px;" alt="create a survey button">

    <button onclick="toggle('gif1')">Show/Hide Animation</button>
    <div id="gif1">
    <img src="images/gifs/sm-1-01.gif">
    </div>

6.	Now you have created the workspace for your survey. Please take a moment to visualize and explore your SurveyMonkey workspace. 

    - On the top ribbon you will see the stages of your survey from “SUMMARY TO PRESENT RESULTS”. 
    - In the left pane you will see that there are icons with option for your survey building process such as “BUILD”, “STYLE”, etc. 
    - In the middle of your workspace, there are also two “QUESTION BANKS” with pre-designed survey questions. On the main area you will see the title of your survey and a green button to design a NEW QUESTION.
    <img src="images/act-1/sm-1-05.png" style="margin-left:10px;width:600px;" alt="new question">
7.	Now that you are more familiar with the SurveyMonkey workspace, let’s start building up our survey about environmental attitudes.
 Click on the green button on the right lower corner that reads **NEW QUESTION** and type in Q1 (question 1) <code>How concerned are you about air pollution?</code> and enter the answers below and finish this question by saving it: 
    ```
    Q1. How concerned are you about air pollution?
    o	Extremely concerned
    o	Very concerned 
    o	Moderately concerned 
    o	Slightly concerned
    o	Not at all concerned
    ```
    
    <img src="images/act-1/sm-1-06.png" style="margin-left:10px; float:right; width:300px;" alt="new question">

    - _Tip! Make sure that multiple-choice option is enabled in the box on the right side of the question, as you can see there are many types of questions we can have, but today we are focusing on Multiple-choice._
    - As you type in you will see this on your screen, don’t forget to save it by clicking on the **SAVE** button at the end of the page.<br><img src="images/act-1/sm-1-07.png" style="margin-left:10px; width:400px;" alt="screenshot">
    - Once you save your first survey question, it will look like this:
    <img src="images/act-1/sm-1-08.png" style="margin-left:10px; width:500px;" alt="first question">
    - Note that there are some boxes for you to edit your question and answers, apply logic to it, copy the question or delete it. Feel free to either explore it or to move to the next step.

    <img src="images/act-1/sm-1-09.png" style="margin-left:10px; float:right; width:200px;" alt="create survey">

8.	Let’s move on and add another question by clicking in the green box **NEW QUESTION**
    - Type in question 2 as below:

    ```
    Q2. How concerned are you about 
    the extinction of endangered animals?
    o	Extremely concerned
    o	Very concerned 
    o	Moderately concerned 
    o	Slightly concerned
    o	Not at all concerned
    ```

    <img src="images/act-1/sm-1-10.png" style="margin-left:10px; width:400px;" alt="create survey">

    - Click **SAVE**.  Your survey should look like the following image:
    
    <img src="images/act-1/sm-1-11.png" style="margin-left:10px; width:400px;" alt="create survey">

    <img src="images/act-1/sm-1-12.png" style="margin-left:10px; float:right; width:300px;" alt="create survey">

9. Proceed and click the **TRIANGLE** next to the button **+NEXT QUESTION** 
    - you can combine different type of questions within one survey. For example, you can have a survey with multiple-choice questions, image choice, comment box, among others! Today we will focus on Multiple-choices only, but you are welcome to explore any options you may want.

    <button onclick="toggle('gif2')">Show/Hide Animation</button>
    <div id="gif2">
    <img src="images/gifs/sm-1-02.gif">
    </div>

10.	Now let’s complete our multiple-choice question survey by adding more questions to it. You can either follow the questions bellow or you can write your own question. Feel free to also explore other types of questions you may be interested in this hands-on part!

 ```
 Q3. The term global warming is often used to refer to the idea that the world’s 
 average temperature may be about 5 degrees Fahrenheit higher in 75 years 
 than it is now. Do you think global warming is good or bad?
 o	Extremely concerned
 o	Very concerned 
 o	Moderately concerned 
 o	Slightly concerned
 o	Not at all concerned

 Q4. Do you believe that society is spending too much time trying to reduce 
 global warming, too little time,  or about the right amount of time?
 o	Much too much
 o	Somehow too much
 o	Slightly too much
 o	Slightly too little
 o	Somewhat too little
 o	Much too little
 o	About the right amount

 Q5. Is reducing global warming more important than improving the economy, 
 less important than improving the economy, 
 or about as important as improving the economy?
 o	Much more important
 o	Somewhat more important
 o  About as important 
 o  Less important 

 Q6. When people get involved in trying to solve environmental problems, 
 how often do you think they make things better?
 o	Always
 o	Most of the time
 o	About half the time
 o	Once in a while
 o	Never

 Q7. How well do you think the environment can recover on its own 
 from problems caused by humans?
 o	Extremely well
 o	Very well
 o	Somewhat well
 o	Not so well
 o	Not at all well

 Q8. Which of the following alternative energy sources do you think will '
 be MOST  important in the next 10 years?
 o	Wind
 o	Solar
 o	Nuclear
 o	Ethanol
 o	Natural gas
 o	Coal
 Other (Please Specify)
 ```

 - _Tip: Note that for the question above you have an open ending option, to add that type it down in the end of the question where it says **Add an “Other” Answer Option or Comment Field**:_

 <img src="images/act-1/sm-1-13.png" style="margin-left:10px; width:600px;" alt="create survey">

 ```
 Q9. Should the universities create more projects or less projects to support 
 alternative energy?
 o	Much more projects
 o	Somewhat more projects
 o	Slightly more projects
 o	About the same amount of projects
 o	Slightly less projects
 o	Somewhat less projects
 o	Much less projects 

 Q10. How often do you recycle?
 o	Always
 o	Most of the time
 o	About half the time
 o	Once in a while
 o	Never

 Q11. How willing are you to change your lifestyle to reduce the damage you may cause 
 to the environment?
 o	Extremely willing
 o	Very willing
 o	Somewhat willing
 o	Not so willing
 o	Not at all willing

 Q12. How likely are you to buy a more expensive product if its packaging is more 
 environmentally-friendly than its competitor’s product?
 o	Extremely likely
 o	Very likely
 o	Moderately likely
 o	Slightly likely
 o	Not at all likely
 ```

 <script>  

    function toggle(input) {
        var x = document.getElementById(input);
        if (x.style.display === "none") {
            x.style.display = "block";
        } else {
            x.style.display = "none";
        }
    }
</script>

[NEXT STEP: Survey Formatting](2-survey-format.html){: .btn .btn-blue }
