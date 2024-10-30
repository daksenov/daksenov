
# Hi there 👋, I'm Dmitry Aksenov

![Profile Views](https://komarev.com/ghpvc/?username=daksenov&color=blue)

## About Me 🚀

```typescript
import { Introduction } from 'introduction.decorator';

@Introduction({
  name: "Dmitry Aksenov",
  location: "Krakow, Poland",
  role: "Senior/Lead Software Engineer",
  hobbies: ["dogs", "photography", "bicyles", "gaming", "hiking", "travelling"]
})
class SoftwareEngineer extends Engineer {
  experience: number;
  passion: string;
  firstComputer: string;
  ageStarted: number;
  learningHabit: string;
  enjoyment: string;
  projectTypes: string[];
  collaboration: string;

  constructor() {
    this.experience = (Date.now() - new Date("2006-03-01").getTime()) / (1000 * 60 * 60 * 24 * 365.25); // 18 years
    this.passion = "technology";
    this.firstComputer = "ZX Spectrum";
    this.ageStarted = 5;
    this.learningHabit = "constantly learn new things";
    this.enjoyment = "building efficient and scalable web apps";
    this.projectTypes = ["professional", "personal"];
    this.collaboration = "collaborating closely with the community";
  }

  getIntroduction(): string {
    return `As a software developer with nearly ${this.experience} years of experience, my passion for ${this.passion} started when I got my first ${this.firstComputer} at ${this.ageStarted}. I ${this.learningHabit}, enjoy ${this.enjoyment}, and work on both ${this.projectTypes.join(" and ")} projects, ${this.collaboration}.`;
  }
}

const developer = new SoftwareDeveloper();
console.log(developer.getIntroduction());
```

## Languages and Tools I Use

![JavaScript](https://img.shields.io/badge/-JavaScript-black?style=flat-square&logo=javascript)
![TypeScript](https://img.shields.io/badge/-TypeScript-black?style=flat-square&logo=typescript)
![Angular](https://img.shields.io/badge/-Angular-black?style=flat-square&logo=angular)
![HTML5](https://img.shields.io/badge/-HTML5-black?style=flat-square&logo=html5)
![CSS3](https://img.shields.io/badge/-CSS3-black?style=flat-square&logo=css3)
![Node.js](https://img.shields.io/badge/-Node.js-black?style=flat-square&logo=node.js)
![Nest.js](https://img.shields.io/badge/-Nest.js-black?style=flat-square&logo=nestjs)
![Git](https://img.shields.io/badge/-Git-black?style=flat-square&logo=git)
![Docker](https://img.shields.io/badge/-Docker-black?style=flat-square&logo=docker)

## Connect with me

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-black?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/aksenovdmitry)
