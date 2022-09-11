# Pavel Bondarenok

---
# Contacts
* Location: Minsk, Belarus
* Phone: +375295620547
* Email: pavel.bondarenok@gmail.com
* GitHub: [Pavel Bondarenok](https://github.com/pbond)
* Discord: Humanist#9322 

---
# About me
I improve my skills in front-end development. 

I am interested in learning TypeScript and React

---
# Skills
* HTML / CSS / JavaScript / Vue.js
* C# / ASP.NET MVC / Entity Framework
* Git
* Jira / Confluence
* MS Office

---
# Code Example
```
const DEFAULT_CONTRAST = 76;
const DEFAULT_BRIGHTNESS = 100;

function themeSwitcher () {
    let style = null;
    return function (theme, contrast, brightness) {
        if (theme === 'dark') {
            style = document.createElement("style");
            style.innerText = `html { filter: invert(100%) contrast(${contrast / 100}) brightness(${brightness / 100}) hue-rotate(180deg) !important; background: #3a3b3b !important; } 
                               img { filter: invert(100%) hue-rotate(-180deg) !important; } `;
            document.querySelector('head').appendChild(style);
        } else {
            style?.remove();
        }
    }
}

const switchTheme = themeSwitcher();
switchTheme('dark', DEFAULT_CONTRAST, DEFAULT_BRIGHTNESS);
switchTheme('light');
```
---
# Expirience
I have been working as a Software Engineer for more than four years.

I make a solutions that increase the productivity and comfort of the customer support team.

---
# Education
* 2009-2013 – Institute of Information Technologies BSUIR
  + Modeling and Computer Design of Radio-electronic Devices

* https://learn.javascript.ru/
  + JavaScript for programmers
  + Modern layout course
  + Vue.js course

___
# Languages
* English: Intermediate (B1)
* Belarusian: Native
* Russian: Native