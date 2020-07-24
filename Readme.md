```ts
import Developer from "@developer/dimaslz"; // import { dimaslz } from '@developer';

console.log(`Profile: ${Developer.profile}`);
// Profile: Software FullStack Developer
console.log(`Name: ${Developer.fullName}`);
// Name: Dimas López Zurita
console.log(`Email: ${Developer.email}`);
// Email: me@dimaslz.io
console.log(`LinkedIn: ${Developer.networks.linkedin}`);
// LinkedIn: https://www.linkedin.com/in/dimaslopezzurita
console.log(`GitHub: ${Developer.networks.github}`);
// GitHub: https://github.com/dimaslz
console.log(`Twitter: ${Developer.networks.twitter}`);
// Twitter: https://twitter.com/dimaslz
console.log(`Site: ${Developer.website}`);
// Site: http://dimaslz.dev
console.log(`Location: ${Developer.location}`);
// Location: Barcelona, Spain
console.log(`I used to work: ${Developer.formerJobs}`);
// I used to work: ["Trovit", "BeRepublic", "FocusOnEmotions", "Zyncro", "Instaply", "Ubeeqo/Europcar Mobility Group"]
console.log(`Interests: ${Developer.formerJobs}`);
// Interests: Entrepreneurship, business, web development, mobile, backend, devops, product, management, ...
console.log(`Motivation: ${Developer.motivation}`);
// Motivation: Work in products with nice objectives
console.log(`Working on: ${Developer.workingOn}`);
// [
//    "https://loremapi.io": "API Studio Design",
//    "https://randomdata.loremapi.io": "Mock API response with custom model",
//    "https://dimaslz.dev": "My personal dev profile. (pending some improvements)",
//    "Others": "Some private products",
// ]
console.log(`Cover letter: ${Developer.coverLetter}`);
/*
  I am a technology geek, with over 10 years of experience as a FullStack  Software Developer.

  Enthusiast and proactive, I have an entrepreneurial mindset, always involved in some side projects in my spare time to keep learning and discover new challenges. 

  Skilled in multiple technologies and platforms (backend, infrastructure, databases, frontend, android, ios, desktop), I am able to adapt to the team's needs. 

  As an employee, I am emphatic and mindful of the product as a whole. I like to understand the business model and team's goals, to be more productive, and proactively think something about what could be a benefit for the user or project. I like to learn, work, and contribute with my code and my positive, supportive attitude. I like to mentor when is needed just like I am happy to be mentored as well.

  Professionally, I am more involved in the JavaScript stack, working the top frameworks in frontend and NodeJS or Go for the backend.

  Being the leader has been a rewarding experience, I would love to have the opportunity to contribute to the team in this role.
*/
console.log(`CV url: ${Developer.cvUrl}`); // CV url: https://cv.lopezzurita.com
```
