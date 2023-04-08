
 HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY
INSTITUTE OF INTERNATIONAL EDUCATION



FINAL ASSIGNMENT

DAT STORE 
E-COMMERCE WEB APP
 

	Subject: 	NEW PROGRAMMING LANGUAGE
	Specialty: 	INFORMATION TECHNOLOGY
	Supervisor: 	MSc. Vu Thi Hanh
	Student’s name: 	Nguyen Thanh Dat	ID: 1911060061






Ho Chi Minh City
2023
SOCIALIST REPUBLIC OF VIETNAM
Independence – Freedom - Happiness
---------
COMMENTS OF THE LECTURER
 
 
Student’s full name:
Student’s name : 	Nguyễn Thành Đạt 	ID: 	1911060061
Lecturer’s comments:
………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………
HCMC………….……………………
Instructor’s Signature
(Instructor’s full name)
 
 
TABLE CONTENTS
OVERVIEW	4
I.	JavaScript	4
1.	What is JavaScript?	4
2.	What role does JavaScript play in the browser?	4
3.	JavaScript Pros and Cons	4
4.	Some JavaScript Development Tools	5
II.	NodeJS	6
1.	Node.js concept	6
2.	Applications should be written in Node.js	6
3.	Misconceptions about Node.js	7
4.	Reasons to use Node.js	7
III.	ReactJS	8
1.	Features of reactjs	8
2.	Why reactjs is the top choice for businesses	9
3.	The future of reactjs	9
ECOMMERCE WEB APP	10
I.	Create API with JSON-Server	10
II.	Some web app features	13
III.	Code structure	17
CONCLUSION	21
REFERENCE	22

 
TABLE FIGURE
Figure 1:Create new folder	10
Figure 2: Input command	10
Figure 3: Add JSON file	11
Figure 4: Run API	11
Figure 5: API in localhost:3000	11
Figure 6: Check API in Postman	12
Figure 7: Web interface	13
Figure 8: Item info	13
Figure 9: Clothes type products	14
Figure 10: Electronics type products	14
Figure 11: Furniture type products	15
Figure 12: Shoes type products	15
Figure 13: Others type products	16
Figure 14: Shopping cart	16
Figure 15: Directory structure	17
Figure 16: App.js	18
Figure 17: apiURL.js	19
Figure 18: store folder	19
Figure 19: store.js	19
Figure 20: pages folder	20
Figure 21: index.js	20

 
OVERVIEW
I.	JavaScript
1.	What is JavaScript?
JavaScript is one of the three main languages of web programming, and it has been widely used for the past 20 years. It was originally called Mocha (1995), then changed to Mona, Livescript, and finally JavaScript as it is today.
As of 2016, 92% of websites today are using JavaScript, and chances are you have used many websites that use this programming language.
2.	What role does JavaScript play in the browser?
Typically, web pages will have JavaScript embedded directly, or will use a .js file to reference. This is a client-side language, which means that instead of processing the script on the website's server, it is downloaded to the visitor's machine and processed on that machine.
It should be noted that there are a number of popular web browsers that allow you to enable/disable JavaScript at your discretion. So, you need to know how the websites you want to visit will be affected without JavaScript working, then decide whether to enable / disable it or not.
3.	JavaScript Pros and Cons
When compared to other competitors, JavaScript has a lot of strengths that can be mentioned below:
	For programmers: This is an easy language to learn, easier to spot and fix. Through JavaScript, programmers can also check input data, to reduce manual testing work. JavaScript is also quite flexible, and it can be used across multiple platforms and browsers, and doesn't require overly complicated tools because they can be compiled by HTML from a web browser.
	For visitors: We can access and interact with the website more effectively. Thanks to their compact nature, they will enable faster web page tasks.
However, every tool will have strengths and weaknesses. Here are some weaknesses that you should consider.
	It is very easy to exploit, so they attract a lot of hackers to search for security flaws to take advantage of, thereby inserting malicious code into the user's computer.
	Flexible support for devices can also create a heterogeneous experience across these devices, and sometimes some browsers will not support the use of JavaScript.
4.	Some JavaScript Development Tools
Currently, with the development of cloud platforms, IDEs that support writing commands in JavaScript are also increasing. The advantage of using cloud IDEs when compared to other text editors is the ability to easily share code with colleagues. Here are some JavaScript development tools that you should know.
	Google Cloud Shell: is the perfect platform for users who need a powerful virtual machine, accessible from any place and time. In particular, if you own a Chromebook, it will be an extremely attractive choice. Currently, Google Cloud Shell is providing 5GB of free storage for users.
	Codetable: This is a very simple IDE, and the code you create above will be executed on the server of the HackerEarth programming platform. Usually, this is the IDE commonly used for programming competitions run by companies. And although they only have basic features, they will be a sufficient choice for beginners.
	JSFiddle: It is one of the most widely used IDEs because of its real-time code checking capabilities, and multi-language support. In addition to basic features like other IDEs, it also has the ability to report bugs through GitHub, or add code to StackOverflow - a question and answer site for professional programmers.
II.	NodeJS
1.	Node.js concept
Node.js is a platform independent built on the Javascript Runtime environment - an extremely fast Javascript language interpreter on the Chrome browser. Based on Node.js, we can build network applications quickly and easily.
Node.js was designed by Ryan Lienhart Dahl - an American software engineer in 2009 and developed under the auspices of Joyent.
The core part of Nodejs is written mostly in C++, so it gives high processing speed and performance.
Applications created by Node.js have fast processing speed, real time real time.
Node.js will be suitable for high-traffic products that need a change in technology and need to scale or create Startup projects as quickly as possible.
2.	Applications should be written in Node.js
	Websocket server: Web socket servers such as Online Chat, Game Server...
	Fast File Upload Client: are high-speed file uploading programs.
	Ad Server: The ad servers.
	Cloud Services: Cloud services.
	RESTful APIs: these are applications that are used by other applications through the API.
	Any Real-time Data Application: Any application that requires real-time speed.
	Micro Services: Node.js can do a good job of breaking down a large application into small services and connecting them together.

3.	Misconceptions about Node.js
Node.js is a platform, not a Framework, and not even a programming language.
Node.js does not support multithreading, it is simply a single-threaded server.
Node.js is not for "newbies", who don't know anything about programming to use because to use Node.js you need to accumulate knowledge of programming techniques, protocols, Javascript,...
4.	Reasons to use Node.js
Nodejs applications are written in javascript, which is quite a popular language. According to the author of the Javascript language, Ryan Dahl: “Javascript has properties that make it very different from the rest of the dynamic programming languages, namely that it does not have the concept of multithreading, it is all about single-threaded and event-driven.”
Nodejs runs cross-platform on Server side, using Event-driven event-driven architecture, non-blocking I/O mechanism makes it lightweight and efficient.
Nodejs application can be run anywhere on Mac - Window - Linux, moreover the Nodejs community is huge and completely free. You can see how big the Nodejs community is here, the packages are completely free.
NodeJS applications respond well to real-time and run cross-platform, cross-device.
 
III.	ReactJS
1.	Features of reactjs
•	JSX: In React, instead of regularly using JavaScript to design website layouts, JSX will be used. JSX is considered simpler to use than JavaScript and allows HTML quoting as well as the use of HTML tag syntax to render subcomponents. JSX optimizes code when compiled, so it runs faster than equivalent JavaScript code.
•	Redux: Redux is a predictable state management tool for Javascript applications. It helps you write applications that work consistently, run in different environments (client, server, and native) and are easy to test. Redux was born inspired by the ideas of the Elm language and Facebook's Flux architecture. Therefore, Redux is often used in combination with React.
•	Single-way data flow: ReactJS doesn't have dedicated modules for handling data, so ReactJS breaks down views into small components that each have a strong relationship with each other. Why should we care about the structure and relationships between components in ReactJS? The answer is the data flow in ReactJS: One-way data flow from parent to child. The fact that ReactJS uses one-way data flow can be a bit difficult for those who want to learn and apply it in projects. However, this mechanism will promote its advantages when the structure and function of the view becomes complex, ReactJS will promote its role.
•	Virtual DOM: Frameworks that use Virtual-DOM like ReactJS when Virtual-DOM changes, we do not need to manipulate the DOM directly on the View and still reflect that change. Because Virtual-DOM both acts as a Model and acts as a View, every change on the Model has led to a change on the View and vice versa. That is, although we do not directly affect the DOM elements in the View, we can still implement the Data-binding mechanism. This greatly increases the application speed – an advantage that cannot be better than using Virtula-DOM.
2.	Why reactjs is the top choice for businesses
In the field of technology development, business owners and developers are always looking for the best methods to give their businesses a better competitive edge. And one of the best technologies that can help businesses stay ahead of the competition in creating web applications is ReactJS.
ReactJS allows businesses to create web applications with better UI to enhance user experience. This is also the technology that businesses need to get higher user engagement, click-through rates and conversions. Moreover, businesses using ReactJS are guaranteed to have a better interface than those using other frameworks because ReactJS helps prevent DOM updates, making the application faster and delivering better UX.
3.	The future of reactjs
Facebook and the entire ReactJS team have always tried to demonstrate their commitment to making ReactJS more efficient. This is a prerequisite to overcome the rapid development of other frameworks like Vue.js. Some expected React updates in the future include:
	There will be new types of rendering like adding unique syntax snippets to JSX without the need for keys.
	Improved error handling. Previously, Javascript errors inside Components would corrupt the component's state and also cause rendering errors in other parent components. These errors are reported very confusingly, making it difficult to fix. Another problem is that in previous versions React did not provide a way to explicitly catch and handle errors and recover from errors in Components.
 
ECOMMERCE WEB APP
I.	Create API with JSON-Server
Step 1: Create new folder and open this folder in VisuaCode
Figure 1:Create new folder
Step 2:Open terminal input command npm install -g json-server
Figure 2: Input command
 
Step 3: add file JSON to folder
Figure 3: Add JSON file
Step 4: run API with command json-server data.json
Figure 4: Run API
Result: API run in http://localhost:3000
Figure 5: API in localhost:3000
Check API in postman
Figure 6: Check API in Postman
 
II.	Some web app features 
Web page interface
 
Figure 7: Web interface
Item info when click item
 
Figure 8: Item info
 
Categorize products by type
 
Figure 9: Clothes type products
 
Figure 10: Electronics type products
 
Figure 11: Furniture type products
 
Figure 12: Shoes type products
 
Figure 13: Others type products
Shopping cart interface
 
Figure 14: Shopping cart
 
III.	Code structure
Directory tree structure
 
          Figure 15: Directory structure
The components directory contains components created and reusable with the Single Page Application (SPA) web type. Components will be called in App.js
 
Figure 16: App.js
Items in green are components that are invoked from the components folder
 
In the apiURL.js class, the BASE_URL variable is used to store the path to the API to be used, here is an API created from JSON-Server with the data source poured in.
 
Figure 17: apiURL.js
In the store directory, there are components responsible for separate functions and are called into the store,js . class
 
Figure 18: store folder
 
Figure 19: store.js
 
In the pages directory, similar to the store directory, the page elements are divided for easy management, the components will be called from the index.js class
 
Figure 20: pages folder
 
Figure 21: index.js
 
CONCLUSION
After I refer to and study the documents available online and listen to lectures in class, I have gained more knowledge about the JavaScript language, knowledge of frameworks that support web programming. Particularly marginal knowledge about creating single API through JSON-Server library, the use of this API helps frontend programmers with a quick tool to run data from the database to complete the features of the page. web without being too fussy about creating a separate API for frontend work. The result is a DAT STORE website using the ReactJS framework and a self-generated API using JSON-Server.
 
REFERENCE
1.	https://aws.amazon.com/vi/what-is/javascript/ 
2.	https://niithanoi.edu.vn/nodejs-la-gi-tong-hop-day-du-ve-nodejs-ban-can-biet.html 
3.	https://vietnix.vn/react-js-la-gi/?gclid=Cj0KCQjw27mhBhC9ARIsAIFsETGJM4iV3yNshCuKX7nDGiMvoWH_VCTbM2Xbw6Y8xwEzo8e6eRkhVIkaApmoEALw_wcB 
4.	https://youtu.be/G4e15f7qfVs 
5.	https://viblo.asia/p/xay-dung-json-server-voi-thu-vien-json-server-07LKX7O45V4 
6.	https://medium.com/@irenemmassyy/create-a-modern-ecommerce-project-with-react-nodejs-express-js-b6a13cd1f9ca 
7.	https://youtu.be/e-KQq-WnJW4 
