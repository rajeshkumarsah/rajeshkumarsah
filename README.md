# Hi there! 👋 Welcome to the profile

## This piece of code will help you understand more about me.

```javascript
const name = "Rajesh Sah";
const experienceYears = 7.4;
const expertise = "I specialize in transforming diverse design concepts into pixel-perfect, adaptable, and scalable digital solutions for businesses. As a developer with over seven years of hands-on experience in UI development, I bring a wealth of expertise to the table. My core strengths lie in Angular and related UI frameworks, where I've honed my skills in crafting seamless user interfaces. I take pride in tackling complex problems, which is a fundamental aspect of my approach to web development. My proficiency extends to mastering web programming skills and a deep understanding of browser behavior, allowing me to create web applications that are both user-friendly and efficient";

// Function to generate a personalized introduction
function generateIntroduction(name, yearsOfExperience, specialization) {
  const greeting = `👋 Hello! I'm ${name},`;
  const experienceInfo = `a frontend developer with ${yearsOfExperience} years of hands-on experience in UI development.`;
  const expertiseInfo = specialization;

  return `${greeting} ${experienceInfo} ${expertiseInfo}`;
}

const introduction = generateIntroduction(name, experienceYears, expertise);

console.log(introduction);
```

## Skills

- **Languages:**  HTML, CSS, JavaScript, 
- **Frameworks/Libraries:** Angular, Jquery, Typescript
- **Design Tools:** Figma, Sketch
- **Version Control:** Git, GitHub
- **Build Tools:** Webpack
- **CSS Preprocessors:** Sass, Scss
- **Responsive Design:** Flexbox, GriBootstrap
- **Testing:** Jasmin & Karma

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Skills Section</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background-color: #f4f4f4;
      margin: 0;
      padding: 20px;
    }

    h2 {
      color: #333;
    }

    ul {
      list-style-type: none;
      padding: 0;
    }

    li {
      margin-bottom: 10px;
    }

    .category {
      font-weight: bold;
      color: #4285f4;
    }

    .skill-list {
      display: flex;
      flex-wrap: wrap;
    }

    .skill {
      background-color: #4285f4;
      color: #fff;
      padding: 8px 12px;
      border-radius: 5px;
      margin-right: 10px;
      margin-bottom: 10px;
    }
  </style>
</head>
<body>
  <h2>Skills</h2>

  <ul>
    <li class="category">Languages:</li>
    <ul class="skill-list">
      <li class="skill">HTML</li>
      <li class="skill">CSS</li>
      <li class="skill">JavaScript</li>
    </ul>

    <li class="category">Frameworks/Libraries:</li>
    <ul class="skill-list">
      <li class="skill">Angular</li>
      <li class="skill">jQuery</li>
      <li class="skill">Typescript</li>
    </ul>

    <li class="category">Design Tools:</li>
    <ul class="skill-list">
      <li class="skill">Figma</li>
      <li class="skill">Sketch</li>
    </ul>

    <li class="category">Version Control:</li>
    <ul class="skill-list">
      <li class="skill">Git</li>
      <li class="skill">GitHub</li>
    </ul>

    <li class="category">Build Tools:</li>
    <ul class="skill-list">
      <li class="skill">Webpack</li>
    </ul>

    <li class="category">CSS Preprocessors:</li>
    <ul class="skill-list">
      <li class="skill">Sass</li>
      <li class="skill">Scss</li>
    </ul>

    <li class="category">Responsive Design:</li>
    <ul class="skill-list">
      <li class="skill">Flexbox</li>
      <li class="skill">Grid</li>
      <li class="skill">Bootstrap</li>
    </ul>

    <li class="category">Testing:</li>
    <ul class="skill-list">
      <li class="skill">Jasmine</li>
      <li class="skill">Karma</li>
    </ul>
  </ul>
</body>
</html>
```


