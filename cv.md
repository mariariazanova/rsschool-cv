# Maria Riazanova

## Contacts
* email: mv_13@mail.ru 
* phone: +375 29 163 09 05
* skype: live:.cid.8fff64d1c38b1fab

## Summary
I’m a beginner in Front-end Development. Hard-working, willing to learn, organized.

## Skills
* HTML5/CSS
* JS
* TS
* React
* Git 
* webpack

## Code samples
```
  saveQuestion = (questiontype, question, answers, correctanswers) => {
    this.setState({questiontype: questiontype, question: question,
                    answers: answers, correctanswers: correctanswers
    });
    const questionInfo = {questiontype: questiontype,
                          question: question, answers: answers,
                          correctanswers: correctanswers}; 
    const questionsInfoNew = this.state.questionsInfo.concat(questionInfo); 
    this.setState({questionsInfo: questionsInfoNew}); 
  } 
  handleSubmit = (EO) => {
    const quizInfoNew = {id: this.state.id, title: this.state.title, 
                         subject:this.state.subject, 
                         form: this.state.form, questions: this.state.questionsInfo};
    this.setState({quizInfo: quizInfoNew, id: this.state.id + 1});                   
    const quizInfoReady=JSON.stringify(quizInfoNew);
    EO.preventDefault(quizInfoReady);
    tasks.push(quizInfoNew);
  }
```
## Experience
* 2020   RSSchool
  * Project: [Web application development with React (a quiz)](https://github.com/mariariazanova/songbird/)
  * Project role: web developer

* 2020   IT-Academy
  * Project: [Web application development with React (a school quiz)](https://github.com/mariariazanova/schoolquiz/)
  * Project role: designer, web developer

* 2020   IT-Academy
  * Project: [Web application development with JavaScript (an image editor)](https://mariariazanova.github.io/image_editor/)
  * Project role: designer, web developer
  
        
* 2019-2020	IT-Academy 
  * Project: [Website development with HTML, CSS & JavaScript](https://mariariazanova.github.io/ntc/)
  *	Project role: web designer, web developer
  
* present time	
  * Svetopribor (head of the deparment of EHS)  
  
## Education
* present time	
  * RSSchool (JavaScript)

* 2020  
  * RSSchool (React)  
  
* 2020  
  * IT-Academy (Web development using React & Angular)
  
* 2020  
  * IT-Academy (Web application development with JavaScript)
  
* 2019-2020 
  * IT-Academy (Website development with HTML, CSS & JavaScript)
  
* International Sakharov Environmental University 

## English
Upper-intermediate. Fluent at speaking, writing and reading.
Other languages - Polish (Beginner), Spanish (Beginner).

## Portfolio
[Github](https://github.com/mariariazanova)
