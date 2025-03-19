# Intro to MERN and MEAN Stack

**Definition/Overview:** MERN and MEAN stack developers are JavaScript web app developers that unite client and server side web development with CRUD database operations (that is to say, *C*reate, *R*ead, *U*pdate, and *D*elete operations). Thus, these positions are said to be 'full-stack' web development positions.
  
#### Table of Contents:

1. [What the Letters Mean](#what-the-letters-mean)
2. [MEAN or MERN?](#mean-or-mern)
3. [The Document Object Model (DOM)](#the-dom)
4. [Supplemental Resources](#supplemental)
  
<hr />

## <a name="what-the-letters-mean">1. What the Letters Mean</a>
  
Each letter in the MERN and MEAN acronyms stands for a technology of the profession's integrated stack. Notice that there is only one letter/technology of difference among the four letters of each (the third letter, which is either an 'R' or an 'A'). The acronyms stand for:

* [MongoDB](https://www.mongodb.com/)
  - A NoSQL (Not Only SQL) database technology, relying on JSON-like documentation (BSON) for data storage.
    + Thus, web asset data is stored via the 'M' of MERN/MEAN stack.  
* [ExpressJS](https://expressjs.com/)
  - A JavaScript framework for building out and establishing server-side ('backend') APIs.
    + This is a technology for handling user/client requests by serving data back as responses.
* [ReactJS](https://react.dev/) *or* [AngularJS](https://angularjs.org/)
  - ReactJS is a client-side library of JS code for creating and customizing user interfaces (UIs) via components. Generally takes less time to learn the basics of than AngularJS.
    + It is one of two options in the MERN/MEAN stack paradigm for implementing User Interface design and User Experience (UX) design, with the other option being AngularJS.
  - ReactJS can be optimized in various ways, such as through:
    + *Debouncing and Throttling* (Limiting when functions execute and how often.)
    + *Lazy Loading* (Loading components on an as-needed basis.)
    + *List Virtualization* (Only rendering list items if they are available on-screen.)
    + *Memoization* (Caching responses for future re-use.)
    + *useTransition() Hook Utilization* (Holding off updates until needed, for performance purposes.)
  - AngularJS is also a client-side UI building technology. However, it is a *framework* and relies on additional technological integrations (e.g., TypeScript).
    + *TypeScript* is an open-source language with the ability to transpile (translate code into another language's source code).
* [NodeJS](https://nodejs.org/en)
  - A runtime environment for executing backend JavaScript code directly in terminal/console, with a gentle learning curve.
    + It works as an engine for processing data and therefore powering web assets, working in tandem with ExpressJS in doing so.
  - Several features of NodeJS include that it is...
    + **Built for fast performance.**
      - The JavaScript *V8 engine* is utilized by NodeJS to empower server-side apps with high efficiency and speed. Microservices, APIs and real-time apps are all popular consumers of the V8 engine.
    + **Enabled JS on both server and client sides.**
      - This supports seamless full-stack integrations, empowering DevOps and CI/CD environments. 
    + **Highly Operating System (OS) portable.**
      - NodeJS is compatible with a variety of Operating Systems, from desktop OSes (e.g., Windows, Linux, macOS) to more specialized ones such as SmartOS and IBM AIX.
    + **Highly scalable.**
      - NodeJS operates under a non-blocking I/O paradigm, which permits users and apps to move onto other tasks and events while an I/O operation is being processed/handled.
    + **Promoted and troubleshot by an active community.**
      - There are a variety of [discussion and other support options](https://nodejs.org/en/about/get-involved) for NodeJS developers. 
    + **Useful for real-time apps.**
      - Since NodeJS specializes in handling concurrent connections, real-time apps (e.g., chat services, online games) can be highly scalable.

<hr />  
  
## <a name="mean-or-mern">2. MEAN or MERN?</a>
  
*MERN* or *MEAN* is spelled out, depending on whether the third technology in the stack is ReactJS or AngularJS. 

**Why choose 'A' over 'R', or 'R' over 'A'?**: In addition to the aforementioned learning curve difference, ReactJS may be better suited for simple web apps while AngularJS can be a more efficacious choice for enterprise web apps that require extensive project maintenance and code consistency. ReactJS is not an intrinsically 'lesser' technology than AngularJS, but can be the superior option for quickly building smaller apps from a tried-and-tested component library with an abstract layer for user interfacing.

Some key differences between AngularJS and ReactJS...  
  
| Characteristic | AngularJS | ReactJS |
| :----: | :----: | :----: |
| JS Support Type | Framework | Library  |
| Learning Curve | More (but not strenuous) | Less (can get started faster) |
| DOM Type | Regular (HTML/XML Standard) | Virtual (increased performance/faster app builds) |
| Components | First Party | Third Party Alternatives |
| Integrated Scripting Technology | TypeScript | JSX |
| Data Binding | 1 or 2 Way | 1 Way |  
  
<hr />  
  
## <a name="the-dom">3. The Document Object Model (DOM)</a>
  
**Wait, what's a DOM?**: The Document Object Model (DOM) represents XML and HTML documents in an object-oriented, tree-structured manner. Examples of objects within this structure include the various *elements*, such as XML/HTML tags, attributes (belonging to various tags), and literal text. The DOM provides a basis for manipulating web asset content, style, and structure through scripting and programming languages, with the potential to dynamically update web pages in real-time.

The root element in the DOM of a .html (web page) file is the html element, or `<html>`, with sub-elements such as `<head>`, `<body>`, and `<a>` (for links, with the attribute `href` used for hyperlink referencing).

<hr />

## <a name="supplemental">4. Supplemental Resource</a>

[Intro to ReactJS](https://github.com/chaseofthejungle/intro-to-reactjs)  
[JavaScript Concepts Guide](https://github.com/chaseofthejungle/js-concepts-guide)

<hr />
  
TODO #1: Add details on real, virtual, and shadow DOM types.  
TODO #2: Add details on React component life cycle.
