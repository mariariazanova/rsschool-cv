https://your-github-account.github.io/rsschool-cv/cv

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

