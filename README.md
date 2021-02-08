# Andrioid-Project-in-Java(Fun Quizzer)
My project is all about  game  which is  Fun Quizzer . This game bundle consist of two games: 
  1) Study Quizzer 
  2) Logo Quizzer 
# Study Quizzer: 
This game consists of  three different category quizzes related to: 
  1. Programming
  2. Geography 
  3. Math’s
  
  
Each category consists of  three different difficulties: 
  1. Easy 
  2. Medium 
  3. Difficult 
  
  
There are 4 different classes and 3 activities: 
  1. **StudyQuizzer(Activity):** The main class of this quiz which manage all classes related to this quiz module 
  2. **QuizContract:** This class contain two different implementation of tables and CategoriesTable and QuestionTable. 
  
  
        a. **CategoriesTable:** Contain one column “name” column 
        
        b. **QuestionTable:** Contain seven column
        
        
            i. Question(contain questions of quiz) 
            ii. Option1 
            iii. Option2 
            iv. Option3 
            v. answerNo(which option is correct) 
            vi. difficulty(Easy ,Medium, Difficulty) 
            vii. category_id(foreign key column with CategoriesTable )
            
            
         3) **Question:** This class contain all questions 
  4) **QuizDbHelper:** This is database class in this questions are stored in database we get all questions through Question Class .We use SQLite database for storage of      questions     
  5) **Category:** Contain Categories (Programming, Geography, Math’s) 
  6) **QuizActivity(activity):** Contain  score , number of questions and timer 
  7) **CreateQuiz(activity):** Through this activity we can create new questions in our quizzes (this part is remaining) 
            
# Logo Quizzer: 
This quiz contain all the logos  of different organizations and different websites. In this quiz we guess the logos and write the  name of logo . We write the spelling of logo from suggested alphabets. Logos  generate  randomly on runtime. 

Logo quizzer contain two different packages: 
1. Adapter  
2. Common 

Adapter contain two different java classes of adapter: 
1. **GridViewAnswerAdapter:** This contain the whole logic of answer of that particular logo on run 
time. 
2. **GridViewSuggestAdapter:** This contain the logic of suggested alphabet’s for logo guess 

Common package contain only one class: 

**Common:** This class contain 3 different static variables: 

  1. User_submit_answer 
  2. Count 
  3. Alphabate_characters             
            
  
  
