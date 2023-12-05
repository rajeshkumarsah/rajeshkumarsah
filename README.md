# Hi there! 👋 Welcome to the profile



<h1 >🚀 Frontend Developer Skills</h1>

<p >
  <i>Transforming design concepts into pixel-perfect!</i>
</p>

## Skills

### 💻 Languages
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### 🛠️ Frameworks/Libraries
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)
![Typescript](https://img.shields.io/badge/Typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

### 🎨 Design Tools
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Sketch](https://img.shields.io/badge/Sketch-F7B500?style=for-the-badge&logo=sketch&logoColor=white)

### 🧭 Version Control
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

### 🛠️ Build Tools
![Webpack](https://img.shields.io/badge/Webpack-8DD6F9?style=for-the-badge&logo=webpack&logoColor=black)

### 🎨 CSS Preprocessors
![Sass](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![Scss](https://img.shields.io/badge/Scss-CC6699?style=for-the-badge&logo=sass&logoColor=white)

### 📐 Responsive Design
![Flexbox](https://img.shields.io/badge/Flexbox-44A2FD?style=for-the-badge)
![Grid](https://img.shields.io/badge/Grid-29ABE2?style=for-the-badge)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

### 🧪 Testing
![Jasmine](https://img.shields.io/badge/Jasmine-8A4182?style=for-the-badge)
![Karma](https://img.shields.io/badge/Karma-0D0C0C?style=for-the-badge)

## This piece of code will help you understand more about me.

```javascript


const name = "Rajesh Sah";
const experienceYears = 7.4;
const expertise = "I specialize in transforming diverse design concepts into pixel-perfect, adaptable, and scalable digital solutions for businesses. As a developer with over seven years of hands-on experience in UI development, I bring a wealth of expertise to the table. My core strengths lie in Angular and related UI frameworks, where I've honed my skills in crafting seamless user interfaces. I take pride in tackling complex problems, which is a fundamental aspect of my approach to web development. My proficiency extends to mastering web programming skills and a deep understanding of browser behavior, allowing me to create web applications that are both user-friendly and efficient";

function generateIntroduction(name, yearsOfExperience, specialization) {
 
  return function() {
    const greeting = `👋 Hello! I'm ${name},`;
    const experienceInfo = `a frontend developer with ${yearsOfExperience} years of hands-on experience in UI development.`;
    const expertiseInfo = specialization;

    return `${greeting} ${experienceInfo} ${expertiseInfo}`;
  };
}

const introductionClosure = generateIntroduction(name, experienceYears, expertise);

const introduction = introductionClosure();

console.log(introduction);
```
