## Andrey Nikitin
### Contact Info
* __City:__ Izhevsk
* __Cell-phone number:__ +7 905 875 65 58
* __e-mail:__ scorpigg@yandex.ru

### Summary
Currently, the IT industry is developing very intensively, as a result, IT companies more and more require programmers. But really literate specialists are not so many, since most want everything at once.
My goal is to become a competent and demanded front-end developer, learn to write beautiful, high-quality code and become part of one of the most demanded companies in the world. Let it take a lot of effort and time, but I think it's worth it.
### Skills
* __Front-end development:__ HTML, CSS, JS
* __Back-end development:__ PHP, MySQL
* __Other:__ Photoshop

### Latest code
```javascript
    btn.addEventListener('click', function(){
        let num1 = parseInt(inp1.value);
        let num2 = parseInt(inp2.value);
        let res;

        switch(oper.value){
            case 'sum':
            res = num1 + num2;
            break;
            case 'sub':
            res = num1 - num2;
            break;
            case 'mult':
            res = num1 * num2;
            break;
            case 'div':
            res = num1 / num2;
            break;
        }

        if(isNaN(res)){
            res = 'Error';
        }

        resBox.innerHTML = res;
        btn.disabled = true;
    });
```