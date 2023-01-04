# Module-4-Quiz-Creation
<h1>Quiz made with API features seen during Module 4</h1>

<h2><strong>Description</strong></h2>

<p>For the Quiz creation, dynamic content was used in order to display different information but in the same sections of the page. Upon starting the Quiz by selecting the start button, the timer starts with 60 seconds and 1 of 5 questions is shown and only changes until the user answers the question. Upon answering the question, the next questions is automatically prompted. If the timer reaches 0, then the page reloads and the process needs to start again.</p> 
  
<p>Depending on the answer the user selects, either the correct or wrong functions are called. If selected answer is correct, then the "correct" function is called displaying the "correct" string and if the answer is incorrect, then a function called "wrong" is called where the "Wrong" string is displayed and 10 seconds are substracted from the timer. Upon answering the question, the next question is displayed and the same process repeats itself until the final 5th question.</p>
  
<p>Upon answering the 5th and final question, another function is called named "show grades" and it displays the amount of correct answers as well the input section where the user types in their initials. Once the user types their initials and clicks on the submit button, these are then stored in local storage and the submit initials button disappears, forcing the user to click on the "Go Back" button which reloads the page and goes back to the initial page where the Quiz can be restarted.</p>

<p>The whole process repeats itself with the exception of the showing grades, which once another user types their initials, these will be shown under the first person's quiz score and acumulates as users do the quiz</p>


<h2><strong>Programming Logic</strong></h2>
<p>The elements that were used to create this quiz were the ones that we saw in class with the exception of the local storage. For this section, I used a function called "reduce" and also used an arrow function to show the acumulated quiz scores and was gotten through stack overflow. Additionally, I received tutoring from a friend who is a senior programmer which assisted in explaning this bit of programming which we have not seen yet as well as explaied the "reduce" function.</p>
  
<h2><strong>What did I learn?</strong></h2>
<p>During this challenge I struggled quite a lot to complete since the topics were confusing for me. Nevertheless, thanks to the holidays, I was able to program little by little everyday and make mistakes in order to understand better how the topics seen in class worked. I probably invested 5-6 hours a day to complete this challenge</p>

<h2><strong>Screenshots and links</strong></h2>
<p>How the webpage should look when opening:</p>
<p>![image](https://user-images.githubusercontent.com/112662397/210482531-cd59e8db-d02f-40b2-a5b6-c7ecea533668.png)</p>

<p>How anwering the correct answer looks like:</p>
<p>![image](https://user-images.githubusercontent.com/112662397/210482712-0a27fb8f-c726-4758-96e1-8c35f4e68376.png)</p>

<p>How answering the incorrect answer looks like:</p>
<p>![image](https://user-images.githubusercontent.com/112662397/210482947-4c5c6723-7c1d-4a6d-b73e-5fa783c3f1a0.png)</p>

<p>How the show grades looks like:</p>
<p>![image](https://user-images.githubusercontent.com/112662397/210483179-2f1d78d2-6ecf-4e8d-8cbb-159d05942adb.png)</p>

<p>How afters submitting your Initials should look like:</p>
<p>![image](https://user-images.githubusercontent.com/112662397/210483334-5d58bad8-829d-4059-98d6-a1faafdb3b95.png)</p>

<p>How the page looks when the timer is finished</p>
<p>![image](https://user-images.githubusercontent.com/112662397/210483590-980e855c-1f80-49f3-971c-466f5f43109c.png)</p>

<p>Link to github pages </p>
<p>https://monteonfrank.github.io/Module-4-Quiz-Creation/</p>

