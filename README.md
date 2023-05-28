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
// I used to work: ["Trovit", "BeRepublic", "FocusOnEmotions", "Zyncro", "Instaply", "Ubeeqo/Europcar Mobility Group", "BackMarket"]
console.log(`Interests: ${Developer.interests}`);
// Interests: Entrepreneurship, business, web development, mobile, backend, devops, product, management, ...
console.log(`Motivation: ${Developer.motivation}`);
// Motivation: Work in products with nice objectives
console.log(`Working on: ${Developer.workingOn}`);
// [
//    "https://loremapi.io": "API Studio Design",
//    "https://randomdata.loremapi.io": "Mock API response with custom model",
//    "https://ng-heroicons.dimaslz.dev": "Heroicons.com for Angular projects",
//    "https://dimaslz.dev": "My personal dev profile. (pending some improvements)",
//    "https://svg-icon-2-fw-component.dimaslz.dev": "SVG icon file to framwork component",
//    "Others": "Some private products",
// ]
console.log(`Status: ${Developer.status}`);
// Status: open as freelancer, mentor and consultant
console.log(`Cover letter: ${Developer.coverLetter}`);
/*
I'm a tech geek, with more than 10 years of experience as a FullStack software developer.

Enthusiastic and proactive, I have an entrepreneurial mindset, always involved in some side projects in my free time to keep learning and discover new challenges.

Skilled in multiple technologies and platforms (backend, infrastructure, databases, frontend, android, ios, desktop), I am able to adapt to the needs of the team.

As an employee, I am empathetic and aware of the product as a whole. I like to understand the business model and the team's goals, to be more productive and proactively think something about what could be a benefit for the user or the project. I like to learn, work and contribute with my code and my positive and supportive attitude.
I like to be a mentor when needed and, I like to be mentored as well.
*/
console.log(`CV url: ${Developer.cvUrl}`); // CV url: https://cv.dimaslz.dev
```
