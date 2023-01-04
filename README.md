# Module-4-Quiz-Creation
<h1>Quiz made with API features seen during Module 4</h1>

<h2><strong>Description</strong></h2>

<p>For the Quiz creation, dynamic content was used in order to display different information but in the same sections of the page. Upon starting the Quiz by selecting the start button,  1 of 5 questions is shown and only changes until the user answers the question and the timer with 60 seconds starts. Upon answering the question, the next questions is automatically prompted. If the timer reaches 0, then the page reloads and the process needs to start again.</p> 
  
<p>Depending on the answer the user selects, either the correct or wrong functions are called. If selected answer is correct, then the "correct" function is called displaying the "correct" string and if the answer is incorrect, then a function called "wrong" is called where the "Wrong" string is displayed and 10 seconds are substracted from the timer. Upon answering the question, the next question is displayed and the same process repeats itself until the final 5th question.</p>
  
<p>Upon answering the 5th and final question, another function is called named "show grades" and it displays the amount of correct answers which were answered as well the input section where the user to type in their initials. Once the user types their initials and clicks on the submit button, these are then stored in local storage and the submit initials button disappears, forcing the user to click on the "Go Back" button which reloads the page and goes back to the initial page where the Quiz can be restarted.</p>

<p>If another user does the quiz, the whole process repeats itself with the exception of the showing grades, which once the other user types their initials, these will be shown under the first person's quiz score</p>


<h2><strong>Programming Logic</strong></h2>
<p>The elements that were used to create this quiz were the ones that we saw in class with the exception of the local storage. For this section, I used a function called "reduce" and also used arrow function to show the acumulated quiz scores and was gotten through stack overflow. Additionally, I received tutoring from a friend who is a senior programmer which assisted in explaning this bit of programming which we have not seen yet as well as explaied the "reduce" function.</p>
  
<h2><strong>What did I learn?</strong></h2>
<p>During this challenge I struggled quite a lot to complete it since the topics were confusing for me. Nevertheless, thanks to the holidays, I was able to program little by little everyday and make mistakes in order to understand better how the topics seen in class worked. I probably invested 5-6 hours a day to complete this challenge</p>

<h2><strong>Screenshots and links</strong></h2>
<p>How the webpage should look when opening:</p>
<p>![image](https://user-images.githubusercontent.com/112662397/208281534-f24a742e-b209-40b2-86bf-5ec4b2192fc2.png)</p>

<p>How the webpage should look when you click on the generate password and all variables are true and with 8 character long password</p>
<p>![image](https://user-images.githubusercontent.com/112662397/208281555-f04d741c-0195-4692-99ef-b5bfd98de1d6.png)</p>

<p>Link to github pages </p>
<p>https://monteonfrank.github.io/Module-3-Password-Generator/</p>

