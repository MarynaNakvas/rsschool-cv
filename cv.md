# Maryna Nakvas
![CV Photo](/photo/photo-cv.jpg)
## Frontend Developer
---
## Contact Information
**Phone:** +48 510 412 663\
**E-mail:** nakvas.maryna@gmail.com\
**Discord:** maryna_nakvas\
[**LinkedIn**](linkedin.com/in/marinanakvas)\
[**Github**](https://github.com/MarynaNakvas)\
---
## Brief Self-Introduction
Results-driven frontend developer with 3.5+ years of professional experience. I am passionate about creating user-friendly, accessible, and responsive web applications using modern technologies. Have a solid knowledge of developing modern responsive web applications. I'm self-motivated, can work in a team and prioritize.\
I like running, hiking in the mountains, walking in the forest and reading good books.
---
## Skills
* HTML, CSS, SASS/SCSS preprocessors, Responsive layouts (Flexbox, CSS Grid)
* JavaScript, TypeScript
* React (React Hooks, React Router, MaterialUI)
* Redux, Redux-Saga, Redux Toolkit, Reselect
* Formik, Firebase, CircleCI, Expo, React Native
* SPA, Web App, Website
* Webpack, ESLint, Stylelint
* Git / GitHub / GitLab / Azure DevOps
* JIRA, Estimation, Mentoring
---
## Code Example
```
const updatedAddendaChanges = Object.entries(groupedAddendas).map(
    ([key, groupAddendas]: AchTemplateChangeAddenda[]) => {
      const updatedGroupAddendas = groupAddendas.map(
        (change: AchTemplateAddendaChange, index: number) => ({
          ...pick(
            change,
            Object.values({
              ...AchTemplateChangeCommonKeys,
              ...AchTemplateAddendaChangeRecordKeys,
            }),
          ),
          [AchTemplateChangeCommonKeys.isApprove]: false,
          [AchTemplateChangeCommonKeys.isReject]: false,
          [AchTemplateChangeCommonKeys.isCancel]: false,
          [AchTemplateChangeCommonKeys.comment]: null,
          [AchTemplateChangeCommonKeys.originIndex]: index,
        }),
      ) as AchTemplateEntryChange[];
      return [key, updatedGroupAddendas];
    },
  );
```
---
## Work Experience
**Sep 2020 – Present time – Frontend Developer, HiQo Solutions, Inc.**
- **Responsibilities:**
    - Client-side UI development
    - Implementation of new functionality and features
    - Optimization of web performance
    - Adhering to modern web development standards and using best practices to create quality interfaces
    - Development of interfaces optimized for working with large amounts of data
    - Communication with customers
    - Collaborating with the backend developer to integrate the client-side and server-side parts of the application
    - Analysis of customer requirements, preparation of estimation
    - Distribution of tasks between developers
    - Taking part in technical interviews, mentoring and knowledge sharing

**Jul 2020 – Aug 2020 – Trainee Frontend developer, HiQo Solutions, Inc.**\
**Aug 2013 – Jun 2020 - Sales Manager, OBKgroup**
---
## Education
**Feb 2020 – May 2020 – IT Academy**
Course: Web application development with React & Angular _(final score: 9)_
Description: React, Redux, Git, GitHub, Webpack, Babel, JSX, Jest, Enzyme
TypeScript, Angular

**Oct 2019 – Jun 2020 – IT Academy**
Course: Web application development with JavaScript _(final score: 9)_
Description: JavaScript, OOP, DOM, SVG, Canvas, Timer, JSON, AJAX, SPA

**Jul 2019 – Sep 2020 – IT Academy**
Course: Website development with HTML, CSS & JavaScript _(final score: 9)_
Description: HTML5, CSS3, Adaptive layout, Animation, Flexbox

**Feb 2019 – May 2019 – hexlet.io**
Course: Basics of programming

**2007 - 2013 – Minsk High Radioengineering College**
Specialization: Information technology software
Achievements: honors degree, average score: 9,0
---
## Languages
* English - B1 (Intermediate)
* Russian - Native speaker
* Polish - A2 (Elementary)
