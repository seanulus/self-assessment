# Self Assessment

### By Sean McDermott

**Self Assessment Questions**

1. Is there anything about the general job search and internship process you feel unprepared for? What would make you feel more comfortable and confident in your job search and internship interviews?

2. Is there anything about searching for and transitioning into your future career in the technical field you feel unprepared for? What would make you feel more comfortable and confident in this process?

**Self Assessment Answers**

1. Personally, I've never felt very comfortable in interviews. While I've been in the culinary industry for some time, the interview process is hardly something to worry about. With so many programmers to choose from though, I'm worried that my "stage fright" will get the best of me in an interview. Situations where I have to "perform" in front of people have always made me uneasy. It's not always a lack of preparedness either. It's just being in the spotlight in general. In order to feel as comfortable as possible, I think it would be good for me to practice interviewing a bit more in practice settings and getting my technical terminology and white-boarding skills to a place where I feel more comfortable.

2. I'm sure I'm not the only person that has "imposter syndrome" at this point. It's a bit frightening to transition from the service industry into the tech industry. While some of my teamwork, communication and problem solving abilities will certainly transfer over, I still feel unprepared in many ways. Once again, I feel like I mostly need to work on interview prep to feel as comfortable as possible moving forward.

### Plan

**My Plan Will Be As Follows**

* Use some time today to finish cover letters and LinkedIn features I didn't finish yesterday.
(finished LinkedIn)(cover letter finished)

* Use time today to go through technical interview questions and come up with thorough and accurate answers to individual questions as a resource/study guide.

* Go through some lessons on Udemy to get a start on React.js and start learning some of the basic concepts.

* Practice some white-boarding questions to get more comfortable handling the process and understand how to talk my way through a problem.

### Work

#### Technical Interview Questions

* What is a framework, and why use it?

A framework is a collection of programs brought together to accomplish a task, make coding more efficient and generally make the lives of coders easier.

* Name every database association relationship.

One-to-one: Both tables can have only one record on either side of the relationship.

One-to-many: The primary key table contains only one record that relates to none, one, or many records in the related table.

Many-to-many: Each record in both tables can relate to any number of records (or no records) in the other table.

* What is an ORM?

ORM stands for Object-Relational Mapping. It is a technique that lets you query and manipulate data from a database using an object-oriented paradigm.

* What is a migration?

Migration is the process of moving from the use of one operating environment to another. This can involve upgrading to new hardware and/or software.

* What is a route?

A route is a "pathway" used to determine which "page" is being viewed by the user. While react doesn't use multiple pages, it gives the user the illusion by routing to different components/properties to display different information.

* What is the difference between a POST and GET request?

A GET request is generally used to retrieve information without changing it. A POST request is usually changing something about the requested information such as changing a password.

* What is Git and why would you use it?

Git is a version control system that allows you to keep track of multiple versions of your projects. This gives you a great advantage because it allows for you access to all previous versions of your code. If you happen to break something along the way, you can go back to a previous version instead of having to start all over from the beginning.

* Which JavaScript frameworks do you have experience with? What are the strengths of those frameworks?

I have experience with Angular and React. Angular is an object oriented framework as where React is a functionally based library. They are both great tools for programmers. Angular allows you to route and pass information through components very easily as well as offering service injection. These are all tools that save a massive amount of time for programmers. React is usable with other JavaScript frameworks and will easily adapt to those circumstances. It's also incredibly fast. The code is much more simple and has fewer bugs in general.

* What happens when a user logs into a website?

* What is a class?

A class is an ES6 JavaScript object that contains a constructor and any methods attached to that class. It is used for creating objects.

* What is an object?

An object can be anything in and object-oriented language such as JavaScript. From strings, arrays, numbers and so on, everything in an object-oriented language is considered an object.

* What is a module? How does it differ from a class?

A module is essentially a library of methods. The difference between a module and a class is that a class can be instantiated and a module cannot. It will only ever be a library of methods. You can however attach these methods to a class.

* Why use a module?

Modules are not always necessary applications, however when you have multiple components/controllers, they can come in handy when you have a few methods you'd like to attach to each of them without having to rewrite the methods every time.

* Give an example of recursion

A factorial problem is a good example of recursion. The function calls itself in order to go through each number leading to the base case. Recursion is sometimes a good practice but can lead to slow runtimes and infinite loops if you're not careful.

* What is unit testing?

It is a level of software testing where individual units/components of a software are tested. The purpose is to validate that each unit of the software performs as designed. It is the smallest testable part of any software.

* What is integration testing?

Integration Testing is a level of software testing where individual units are combined and tested as a group. The purpose of this level of testing is to expose faults in the interaction between integrated units.

* What happens when a user types in a URL?

First, the browser checks the caches for the browser, operating system, router and finally the internet service provider. If the URL is not cached then the ISP's DNS server initiates a DNS query to find the IP address of the server that hosts the searched website.

* What is string interpolation?

String interpolation in ES6 is known as template literals. It allows you to use variable values in strings using the correct syntax. In JavaScript this is `String of words ${variable}`.

* How do local and instance variables differ?

Scope: Local variables are visible only in the method or block they are declared whereas instance variables can been seen by all methods in the class.

Place where they are declared: Local variables are declared inside a method or a block whereas instance variables inside a class but outside a method.

Existence time: Local variables are created when a method is called and destroyed when the method exits whereas instance variables are created using new and destroyed by the garbage collector when there are no reference to them.

Access: You can't access local variables whereas instance variables can be accessed if they are declared as public.

Where they are declared: Local variables are declared in a method or a block before they are called, whereas instance variables can be declared anywhere in the class level (even after their use).

Instance variables always have a value even if they're not assigned one. Local variables without a value will give you an error.

* What is a foreign key?

A foreign key is a column or group of columns in a relational database table that provides a link between data in two tables. It acts as a cross-reference between tables because it references the primary key of another table, thereby establishing a link between them.

* What is REST?

REpresentational State Transfer is an architectural style for providing standards between computer systems on the web, making it easier for systems to communicate with each other. REST-compliant or RESTful systems are characterized by how they are stateless and separate the concerns of client and server.

* What do you think the best practices are for branch management in a multi-developer project?

The way I've experienced success is by splitting the workload into separate parts so there isn't much of a chance of anyone writing over another persons code and creating conflicts. It all comes down to good communication with your team and making sure everyone is on the same page.

* How would you parse a JSON string?

I would likely use the JSON.parse() method.

* What is HTTP and why do we use it?

HTTP is Hypertext Transfer Protocol. It is the foundation of data communication for the World Wide Web. We use it to transfer data between servers and clients(ie Web Browsers). This allows the client to get all the files necessary to load the page for any website.

* What is the difference between a private and a public method?

A private method is accessible only by the class that contains it. A public method can be accessed by any class.

* How would you grab an element from the DOM using jQuery?

Generally speaking, you grab elements from the DOM with jQuery by naming the class/id of whatever element you are trying to affect. The syntax usually looks like $('DOMelement').someMethod();

* Describe a callback functionally

A callback function (higher order function) is a function that is passed to another function as a parameter and executed inside that function.

* What is an array?

An array is an object in JavaScript that can contain other objects such as strings, numbers, boolean values, other arrays and objects.

* Explain MVC

MVC stands for Model/View/Controller or Component depending on which language/framework you're dealing with. The Model defines what data the app should contain. The view defines how the apps data should be displayed to the user. The controller/component contains logic that updates the model and/or view in response to input from the user.

* Describe Object Inheritance

In object oriented programming, object inheritance refers to the ability of new objects to take on the properties of existing objects. You can inherit properties of a different object using the extends keyword.

* What is floating in CSS?

Float is a property in CSS which specifies that an element should be placed along the left or right side of its container, allowing text and inline elements to wrap around it. The element is removed from the flow of the webpage, though still remaining a part of the flow.

* What are media queries and how do you use them?

Media Queries are used to determine breakpoints in the browsers view based on screen size or some other feature. They are generally used in responsive design to make sure that all the content of a page is visible and easily readable to the user on any device.

* How do you make images usable for blind people who are using a screen reader?

Inside the img tag, you write your definition of the image in the alt section for example <img src="img/dog.jpg" alt="a picture of a dog">

* Whats the difference between =, ==, === in JavaScript?

The = sign is used to assign a value to something, usually a variable. The == and === are commonly used to compare two objects and determine a boolean value of true or false depending on the outcome.

* What's the difference between an undefined and undeclared variable in JavaScript?

An undefined variable is a variable that has been declared bunt no value exists and is a type of itself 'undefined'. An undeclared variable is a variable that has been declared without a var, let, or const keyword.

* What's your favorite language and why?

So far, JavaScript has been my favorite language. As a language, it encompasses the vast majority of front end functionality and there are still so many advancements to be made to this ever expanding technology.

* You've been working on a site for a couple months here at our company. You come in one day and the site is down. What do you do?

First, I would communicate with the team to see if there had been any discoveries into what was happening. If there had been anything, I would want to make a plan of action to get the site up and running. If there had been no breakthroughs yet, I would suggest that we take time to figure out why the site crashed and take steps to uncover that information before moving ahead with any sort of fix.

### Reflection & Next Steps  

**Questions**

  1. Do you feel like you made improvement today? Are you more confident and comfortable in one or more areas? Why or why not?

  2. Where are you at now? What are your next steps? What do you still need to accomplish to feel confident and prepared to begin your eventual job search?

**Answers**

  1. I do feel like I made some improvement today. I mainly wanted to focus on things related to interview prep so I went through and found answers to questions I didn't know as well as writing out answers to the questions I did. I feel like I'll have a somewhat better understanding of what the interviewers are looking for in terms of technical questions in the interview.

  2. Next steps will be working on white-boarding and getting live interview practice with some classmates if at all possible. In the future I would like to focus on getting better at algorithms as well and striving to be in a place where I feel like I can't be more prepared which may not happen. There is plenty to learn yet.
