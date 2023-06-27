![50964909_2048998301862397_48000910982381568_n](https://github.com/KarinaSamr/rsschool-cv/assets/137826507/c9aa7fc4-2e24-449b-8949-71e1c0000cef)

## Karina Samarina  
Junior Frontend Developer

---

### Contact Information:

**Phone:** +4917669375599  
**E-mail:** samarinakarin@gmail.com  
**Discord rs_school:** tali_sam  
[Behance](https://www.behance.net/karinasamarina)  
[LinkedIn](https://www.linkedin.com/in/karina-samarina-519b8897/)  

---

### About me:

 In my life I had opportunity to finish education and work in different fields, such as law, teaching, translation and SEO, but for different reasons I decided not to pursue them and change my professional goals entirely. Two years ago I became very interested in graphic design and I managed to finish several courses and create a portfolio, but at the same time I started learning C and Python, which in combination with my interest in graphic design lead me to the Frontend Development. I am very passionate and curious and I love to learn new skills and challenge myself, hopefully it will lead me to the Frontend Developer position. 

---

### Education

- JavaScript course udemy.com
- Python course freeCodeCamp.org
- CS50 (Computer Science Harvard)
- BA in Baltic Management Studies Hochschule Stralsund, Germany

---

### Experience

- Marketing and SEO Intern at SIXT, Germany
- SMM and Event management, Hochschule Stralsund, Germany
- Leading coordinator in International Office, Izhevsk Technic University, Russia

---

### Skills

- HTML/CSS
- JavaScript basics
- Python basics
- C basics
- Adobe Photoshop, InDesign, Illustratot
- Figma

---

### Languages

- Russian (native)
- English (C1)
- German (B1)

---

### Code Example

***Task on codewars.com:***   
ROT13 is a simple letter substitution cipher that replaces a letter with the letter 13 letters after it in the alphabet. ROT13 is an example of the Caesar cipher. 
Create a function that takes a string and returns the string ciphered with Rot13. If there are numbers or special characters included in the string, they should be returned as they are. Only letters from the latin/english alphabet should be shifted, like in the original Rot13 "implementation".

***Solution:***  

        function rot13 (message) {

            let newStr = '';
            for (let i = 0; i < message.length; i++) {
                let code = message.charCodeAt(i);
                if (code >= 65 && code <= 90) {
                    code += 13;
                    if (code > 90) code = code - 26;
                    newStr += String.fromCharCode(code);
                } else if (code >= 97 && code <= 122) {
                    code += 13;
                    if (code > 122) code = code - 26;
                    newStr += String.fromCharCode(code);
                } else {
                    newStr += String.fromCharCode(code);
                }
            }
            return newStr;
        }

### Finished projects

- [CV](https://github.com/KarinaSamr/rsschool-cv/blob/gh-pages/cv.md) 
