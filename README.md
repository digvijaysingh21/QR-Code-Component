# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Code Snippet](#code-snippet)
  - [Continued development](#Continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)



## Overview

Learning responsive layout .

### Links

- Solution URL:(https://github.com/digvijaysingh21/QR-Code-Component.git)
- Live Site URL:(https://qr-code-component-sigma-virid.vercel.app/)

## My process
Create a container inside this create a card and keep oyur image and text in this section and style accordingly.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

This project help me in learning how to center a div 
and setting a card and image inside it with knowlede of flexbox,padding,mrgin and some border property.

### Code snippet

```html
<body>
<div class="container">
  <div class="card">
    <img  src="images/image-qr-code.png" alt="qr-code-img">
    <div class="text">
      <h2>
        Improve your front-end skills by building projects

      </h2>
      <p> Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
    </div>
  </div>
</div>
 
</body>
```
```@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap');

:root{
  --white: hsl(0, 0%, 100%);
  --light-gray: hsl(212, 45%, 89%);
  --grayish-blue: hsl(220, 15%, 55%);
  --dark-blue: hsl(218, 44%, 22%);
}

*{
  margin: 0;
  padding: 0; 
}



body{
  font-family: 'Outfit', sans-serif;
  background-color: var(--light-gray);
  font-size: 15px;
  display: flex;
  align-items: center;
  min-height: 100vh;
}

.container{
   margin: 0 auto;
   max-width: 360px;
}

.card{
  background-color: var(--white);
  box-shadow: 5px 5px 5px rgba(0,0,0,0.3);
  text-align: center;
  margin: 0 1em;
  padding: 18px;
  border-radius: 18px;
}
.card img{
  max-width: 100%;
  border-radius: 12px;
}

.text{
  padding: 22px 10px;
}

.text h2{
  color: var(--dark-blue);
  padding-bottom: 15px;
}

.text p{
  color: var(--grayish-blue);
}
```




### Continued development

 Looking forward to learn new topics like animation, specificity, z-index.


### Useful resources

- [Markdown Guide](https://www.markdownguide.org/getting-started/) - This helped me for writing md. I really liked this pattern and will use it going forward.

- [W3schools CSS](https://www.w3schools.com/css/) - This is an amazing article which helped me finally understand CSS concepts. I'd recommend it to anyone still learning this css concept.



## Author

- Frontend Mentor - [@digvijaysingh21](https://www.frontendmentor.io/profile/digvijaysingh21)





