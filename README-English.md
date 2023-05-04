## Basic Information

Name：Li,Shuxue&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Gender：Male

Phone：15822472510&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Email：1149926505@qq.com

University：Tianjin University of Commerce

Major：Computer Science and Technology

Experience：7 years&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Blog：https://lishuxue.site

&nbsp;

## Personal Strengths

1、Undertook technical projects and successfully implemented and deployed numerous projects.

2、Deep understanding of the JavaScript language, understanding of underlying mechanisms such as Babel compilation and V8 execution.

3、Proficient in frameworks such as Vue and React, familiar with TypeScript, and able to use them in project development.

4、Familiar with front-end engineering tools such as Webpack and Vite, able to write custom plugins or loaders to achieve specific functions.

5、Familiar with Node.js, Koa, databases, can develop backend API services through Node.js. also able to develop some CLI tools or middleware.

6、Familiar with mobile development such as H5 and MiniProgram, familiar with native development and hybrid development.

&nbsp;

## Work Experience

2021.5--now&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Mei Tuan&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Front-End

2016.4--2021.4&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Standard Chartered&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Front-End

&nbsp;

## Project Experience

### Mei Tuan&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;Business Management System

**Description:**  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Backstage management system for merchants. This system is mainly used by operating personnel, such as reviewing the products built by merchants, scheduling shelves, fulfilling contracts, and so on. The technology stack is Vue, which uses a preferred component library based on Element secondary encapsulation, and a mode in which the front and back ends are separated.

**Role:** Core Developer

**Experience:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;After 2 years of rapid development iterations, the structure and code of the project are already very heavy. The page runs relatively sluggish, especially on low-end computers, the page even becomes a slideshow. Because the business is very complicated, it directly leads to abnormally bloated page code, poor readability, and online accidents are prone to occur, so the project is restructured and optimized.

1. Overall architecture: more detailed splitting of main files, project configuration TS, enhanced code maintainability and readability
2. Code level: reduce data fields and nested fields in a targeted manner to speed up the initialization of vue2 code, responsiveness, etc.
3. Page layout: singleness. Try to persuade the product to separate the functions with less strong business logic into different pages, so as to effectively improve the loading speed and performance of each page.

&nbsp;

### Mei Tuan&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;Business Mini Program

**Description:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;As a small program for merchants across the country, the merchant-side small program carries a lot of related functions of merchants, such as: building/maintaining products, reviewing, uploading /Removal, scheduling, delivery, fulfillment and other functions.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;At the same time, as a small program with complex business, many functions, many users, and DAU exceeding one million, how to reasonably carry out project development, maintenance iteration, project configuration, and organizational structure , code development, etc. are very important.

**Role:** Core Developer

**Experience:**

1. Daily development, maintenance iteration, code-review, optimization and refactoring, technical solution selection, etc.

1. Mini program core list freeze optimization, the list is divided into 3 lists, use tab to switch, freeze problem troubleshooting and optimization.
   As the most used page, this page has many functions and is complex, combining various filters and displaying various business-related information. The project ran until the end of 2022, and the loading time of the first screen once reached 5-8s. After careful research and investigation, a detailed solution was formulated.
   1. List lazy loading (before entering the first tab will also load the second tab data)
   2. List loading data cache (the loaded list is no longer loaded repeatedly, remember the scrolling distance, etc.)
   3. Delayed loading of some nodes (calendar filter item nodes are delayed in rendering, and some are rendered in click-to-open calendar events)
   4. Reduce the number of setdata (from the initial 200+, to below 50)

&nbsp;

### Mei Tuan&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;Code Quality Metrics Platform

**Description：**  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Providing a comprehensive, flexible, and professional quality measurement and governance service platform for applications.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1. Full coverage of the development cycle: supporting quality measurement and control in the entire life cycle of the development (local submission, pull request, release, and Online inspection).  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2. Flexible customization: projects can freely select different measurement rules (Lint and Non-Lint), control stages and thresholds, etc.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3. Open rule market: rules generated by online project problems and other dimensions, are published on the platform and can be freely used by other teams. If not satisfied, they can also create rules and publish them to the market for all teams to use.

**Role：** Core Developer

**Technology:** ESLint secondary packaging, ESLint custom plug-in, create scaffolding, Nodejs, database, etc.

**Difficulties:**

1. What are the differences or advantages of directly configuring ESLint in existing projects?
2. How to ensure that users are willing to use and solve all the problems. If there are many problems, users are generally resistant to solving them?
3. How to control at different key stages, and how to ensure that the stages is actually controlled. If the user skips it forcibly, will there be a bottom strategy?
4. How can users quickly implement their own rules?

**Achievements：**  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Currently, a total of 6 teams have been connected, with 37 projects covered, which includes different technology stacks such as Vue, React, MiniProgram, and also supports JavaScript and TypeScript.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;On average, hundreds of submissions are controlled every day, Pull-Request is checked and the results are pushed to the group dozens of times, and online inspections scan and detect up to thousands of code issues per day (waiting repair).

&nbsp;

### Mei Tuan&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;Deprecated Code Analysis

**description:**  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;As the project iterates, some historical pages or codes may no longer be used and maintained. This tool can analyze obsolete code files in the code repository, find out obsolete pages, low traffic pages, obsolete files, referenced but unused files, useless code blocks, etc. The report is displayed to promote the deletion management of each group.

**Role:** Owner

**Technology:** Babel compilation, AST traversal, Nodejs, etc.

**Difficulties:**

1. How to analyze the dependencies of files, and how to deal with loops in dependencies?
2. How to identify the referenced but unused files, a file may be referenced and not used in file A, but may be used in file B.
3. How to find useless code blocks?

**Achievements:**  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A total of 26 front-end projects of the optimal product terminal were analyzed, and thousands of discarded files were analyzed in total. Code construction time, package size and number of files, etc., local startup time, and performance have also been significantly improved.

&nbsp;

### Mei Tuan&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;User Information Collection SDK

**Description：**  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Through non-intrusive buried points, directional collection of user data during PC-side operation, such as entering the page (PV), a module on the page displays (MV), click the button (MC), Send request (RQ), page jump link (LK), etc. According to the collected data, configure the user's key action link monitoring to realize real-time alarm when the key action is interrupted.

**Role:** Owner

**Technology:** Front-end monitoring, Service Worker, Typescript, etc.

**Difficulties:**

1. How to collect key data and how to report?
2. How to do it without intrusion?
3. How to determine key links and monitor composite indicators?

**Achievements：**  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A total of 10 important items of the preferred product terminal are connected to the SDK, and hundreds of key actions of online users are monitored every day, and more than ten times are found to be due to unrobust code If the user behavior is interrupted, the relevant person in charge will be alerted in time to make it repair or roll back, avoiding the expansion of the problem.

&nbsp;

## Personal Summary

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Strong learning ability, problem-solving ability, and executive ability. No matter what intractable diseases I encounter at work, I can solve them quickly and smoothly. I am also constantly learning new knowledge to ensure that I will not be left behind by the industry.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I also developed my own [personal site](https://lishuxue.site) in my spare time to record some usual study notes and share them with everyone. For things that I don't know, I will dig into the root of the problem to explore the underlying principles and mechanisms.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;At the student and working stage, I am relatively good, and some of my past honors are listed below:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**During College**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2014 First-class Scholarship](https://cdn.lishuxue.site/resume/images/2014yideng.jpeg)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2015 First-class Scholarship](https://cdn.lishuxue.site/resume/images/2015yideng.jpeg)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2016 First-class Scholarship](https://cdn.lishuxue.site/resume/images/2016yideng.jpeg)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2014 Excellent Student](https://cdn.lishuxue.site/resume/images/2014sanhao.jpeg)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2015 Excellent Student](https://cdn.lishuxue.site/resume/images/2015sanhao.jpeg)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2016 Excellent Graduate](https://cdn.lishuxue.site/resume/images/youxiubiye.jpeg)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Campus Outstanding League Member](https://cdn.lishuxue.site/resume/images/youxiutuanyuan.jpeg)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Intermediate Software Designer](https://cdn.lishuxue.site/resume/images/ruanjiansheji.jpeg)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[C Language Proficiency Level 2](https://cdn.lishuxue.site/resume/images/c2ji.jpeg)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Inspirational Scholarship

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**During Work**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Best Newcomer of 2017  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Best Employee of 2018  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Best Team of 2019  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Outstanding Team Member of 2020  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Spring Star of 2022](https://cdn.lishuxue.site/resume/images/zhongduanzhixing.png)
