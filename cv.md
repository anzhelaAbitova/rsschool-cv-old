# My resume 
## Anzhela Abitova 
        
My Email anzhela.abitova@mail.ru, telephone number +79608138825, my profiles on 
[VK](https://vk.com/id230631255"), [Facebook](https://www.facebook.com/abitovaanzela").
        
My main goal is to become a successful web-developer. Now I engage in web-design. But I 
find coding much more fascinating and reliable. I have to admit my lack of actual experience. 
All projects I did contribute were training. But I do learn fast, especially when I'm 
inspired. And I'm inspired to learn coding. 
        
I know HTML, CSS and currently trying to learn JavaScript and PHP. 
        
Education that I've had so far are course Web-design at Samara University, courses at HTML 
Academy and various online-seminars (mostly Skillbox), a lot of books and articles. 
        
I have learned English at school, then had three courses at university. For the most part 
all practice I had with English is reading a lot and watching courses. 
        
As I said previously I've had contributed to some training projects, links provided above, and had 
badges at HTML Academy.
        
[Page from HTML Academy](https://htmlacademy.ru/assets/courses/309/project-state-final.zip")
        
Examples of my code:
```javascript
const $getElById = (id) => document.getElementById(id);
const random = (num) => Math.ceil(Math.random() * num);

function tapCounting(btn, tapLimit){
  let count = 0;
  return function(){
    count++;
    btn.querySelector('span').innerText = tapLimit - count;
    if (count >= tapLimit) {
       btn.disabled = true;
    }
       return count;
  }
}

function minmaxDamage(item) {
    let damageArr = [item.maxDamage, item.minDamage];
    return damageArr[random(1)];
}

let selectorsM = {
  selectors(name) {
    this.elHP = document.getElementById(`health-${name}`);
    this.elProgressbar = document.getElementById(`progressbar-${name}`);
    this.namePlayer = document.getElementById(`name-${name}`);
    this.imgPlayer = document.getElementById(`img-${name}`);
 }
}

export {$getElById, random, tapCounting, minmaxDamage, selectorsM };
```
