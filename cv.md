## Fedor Parenkov

![](./assets/img/profile_photo.png)

### Contact Info
**Location:** Samara, Russia  
**Email:** parenkov.fedor@gmail.com  
**Telegram:** [@wakeuptheo](https://t.me/WakeUpTheo)  
**Discord:** wakeuptheo#1283

### About Me

I have some no commercial experience in manual and automated testing, which includes training courses and part-time tester employment. Currently my goals is get enough knowledge and practice required for junior software engineer position in Frontend development. I think my strengths are patience, perseverance and willing to learn new things.

### Links
[**GitHub**](https://github.com/wakeuptheo?tab=repositories)    
[**LinkedIn**](https://www.linkedin.com/in/fedor-parenkov/?locale=en_US)

### Skills
* HTML/CSS
* Git
* [JavaScript Basics](https://www.codewars.com/users/wakeuptheo)
* [Python Basics](https://py.checkio.org/user/WakeUpTheo/list/)
* Java Basics
* Testing Frameworks and Tools: Selenide, JUnit, REST Assured, Jenkins, Allure, Postman, Appium, SoapUI, JMeter
* MS SQL Server 

### JavaScript Code Example from Codewars ("WeIrD StRiNg CaSe" 6 kyu kata)
**Task description:**  
Write a function `toWeirdCase` that accepts a string, and returns the same string with all even indexed characters in each word upper cased, and all odd indexed characters in each word lower cased. The indexing just explained is zero based, so the zero-ith index is even, therefore that character should be upper cased and you need to start over for each word.
The passed in string will only consist of alphabetical characters and spaces. Spaces will only be present if there are multiple words. Words will be separated by a single space.

My solution:

```
function toWeirdCase(string) {
    let tempStorage = string.split(' ');
    let result = [];

    tempStorage.forEach((element) => {
        for (let i = 0; i < element.length; i++) {
            if (i % 2 === 0) {
                result.push(element[i].toUpperCase());
            } else {
                result.push(element[i]);
            }
        }
        result.push(' ');
    });
    return result.join('').trim();
}
```
```
toWeirdCase("Hi there! My name is Fedor.") => output: "Hi ThErE! My NaMe Is FeDoR."
```
### Experience
I have no work experience relevant to software development at this time.

### Trainings
[**JavaScript/Front-end Pre-School 2022Q2 (RS School)**](https://rs.school/js-stage0/)  
[Certificate](https://app.rs.school/certificate/qsuzhbgq)  
[An educational project](https://rolling-scopes-school.github.io/wakeuptheo-JSFEPRESCHOOL2022Q2/travel/)

[**HTML5 & CSS3 Basics Course (Stepik)**](https://stepik.org/course/58973/promo)  
[Certificate](https://stepik.org/cert/1517607)

[**Version Control with Git (EPAM Learn Digital Platform)**](https://learn.epam.com/detailsPage?id=601f195a-d408-4439-a16d-0630ed2a412e)

### Education
**Samara National Research University**  
Organization and Technology of Information Security  
2020

**Samara State Transport University**  
Information Transmission Systems  
2005 – 2009

### English
[**A2 Elementary**](https://www.efset.org/cert/d2MGwU)  
I keep learning to improve my language skills.