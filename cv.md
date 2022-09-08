# Maksim Aniska
<img src = "https://avatars.githubusercontent.com/u/106627293?v=4" width = "240" height = "240" alt = "still young Maksim Aniska photo" />

## Some facts about me
Born in 1982. I am 40 this year.

1999 - 2002 Studied at the Belarusian State University at the Faculty of Journalism (did not graduate)

2002 - 2003 Served in the army.

2006 - 2021 Worked and did business in the construction sector (concrete production) and in the field of cargo transportation.

I started as a foreman of the plant site, then became a sales manager, head of the sales department, the last position was the deputy director of the company.

I have my own business related to cargo transportation, which currently operates autonomously, without my participation.

I am married and have a son, Matthew. This year he will be 2 years old.

My goal is to move with my family from Belarus.

## Skills

I am well organized, structured, disciplined and motivated.

I have good communication skills, I have a great desire to develop and learn new things.


## Achievements


<a href = "https://www.efset.org/cert/reYjvv">**Certificate EF SET C1 Advanced**</a>


<img src = "https://ibeton.by/wp-content/uploads/EFSET_MaksimAniska.png" href = "https://www.efset.org/cert/reYjvv" width = "330" height = "330" float = "left">


<a href = "https://stepik.org/certificate/756e53216330284945e45bdf3ec116229277adf0.pdf">**Stepik JavaScript courses Certificate**</a>


<img src = "https://stepik.org/certificate/756e53216330284945e45bdf3ec116229277adf0.png?resolution=small" float = "left">


**Examples of my code**
```
'use strict';

function collectAllNumbersInInterval(firstNumber, secondNumber) {
    let result = " "; //result will contain the list of all numbers between the firstNumber and secondNumber
    if (firstNumber > secondNumber) {
        for (let i = firstNumber; i >= secondNumber; i--)
            result += firstNumber-- + " ";
        firstNumber--;
    } else if (secondNumber > firstNumber) {
        for (let i = secondNumber; i >= firstNumber; i--)
            result += secondNumber-- + " ";
        secondNumber--;
    } else if (firstNumber === secondNumber) {
        result = firstNumber;
    }
    return result;
}
```

```
'use strict';

function testCycle(n) {
    const resheto = [];
    const num = [];
    for (let i = 2; i < n; i++) {
        if (!resheto[i]) {
            num.push(i);
            for (let j = i * 2; j < n; j += i) {
                resheto[j] = true;
            }
        }
    }
    return num.join(" ");
}
```

## Contacts and links
### Call\Viber\Telegram
* +375 29 63 73 666
* +375 29 63 13 666
### Email
aniskamaksim@gmail.com
### GitHub
https://github.com/aniskamaksim
### Codewars
https://www.codewars.com/users/aniskamaksim