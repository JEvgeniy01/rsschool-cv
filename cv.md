# Evgeniy Turov


## Contacts


**E-mail:** evgeniy.turov@mail.ru  
**Telegram:** @EvgenyTurov  
**GitHub:** https://github.com/JEvgeniy01  
**Discord** Evgeniy(@JEvgeniy01)

## About me  


I am 26 years old a bridge engineer with three years of work experience on difficult complicated construction objects. At this time I have been studying for Frontend-developer. I have been studying already about 1.5 years. It is important to me that in this area of IT you can almost immediately see result of your work. I believe that my work experience and my desire to learn a new profession will help me to become successful in web-development.

## Skills  


- HTML
- CSS, SASS
- Javascript, ES6
- Git, GitHub

## Code example    
_The problem is to write a function to find the average of the three scores passed to it and returns the letter value associated with each grade._


```
function getGrade (s1, s2, s3) {
  let averageNum = (s1 + s2 + s3) / arguments.length;
  let averageSystem = {
    A: '90-100',
    B: '80-90',
    C: '70-80',
    D: '60-70',
    F: '0-60',
  };
  for (let [key, value] of Object.entries(averageSystem)) {
    let tempArr = value.split('-')
    let marks = tempArr.map(item => +item);
    if(averageNum >= marks[0] && averageNum <= marks[1]) {
      return key;
    }
  }
}
```

## Experience  


- **Employee search page** (HTML, CSS, Vue): [Search page](https://github.com/JEvgeniy01/jilford-test-search_page)
- **Curriculum vitae** (Markdown): [CV](https://github.com/JEvgeniy01/rsschool-cv)

## Work Experience  


**University:** Siberian Transport University, Bridges and Tunnels Faculty


**Courses:**

- Interactive Javascript course on [learnjavascript.ru](https://learn.javascript.ru)
- "Basic Git" course from Yandex
- React courses on [youtube](https://www.youtube.com)

## English Language  


**B1** (I have the international certificate "City&Guilds" confirming the level)
