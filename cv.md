# Daniil Petrov
## Contacts
[GitHub](https://github.com/dapetrov)
[VK](https://vk.com/no_future8)
## About me
Student. Keep learning HTML/CSS
## Skills
* HTML
* CSS
* C++
* Git
* Java
* IC2
* Dota 2
* Markdown
## Code examples:
```javascript
function tickets(peopleInLine){
    let c25 = 0
    let c50 = 0
    let c100 = 0
    for (let i = 0; i < peopleInLine.length; i++) {
        if(peopleInLine[i]===25){
            c25++
        }
        if(peopleInLine[i]===50){
            if(c25>0){
                c50++
                c25--
            }
            else return 'NO'     
        }
        if(peopleInLine[i]===100){
           if(c25>0&&c50>0){
                c25--
                c50--
                c100++
            }
            else if(c25>=3){
                c25-=3
                c100++
            }
            
            else return 'NO'
        }
    }
    return 'YES'
}
```
## Education
Tver State Unviversity(2019-2023)
## English level
A1