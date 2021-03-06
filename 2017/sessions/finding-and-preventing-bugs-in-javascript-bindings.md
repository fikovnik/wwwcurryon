---
layout: 2017-abstract
title: "Finding and Preventing Bugs in JavaScript Bindings"
by: Deian Stefan
affiliation: UC San Diego
profpic-class: deian_stefan
---

[@deiandelmars](https://twitter.com/deiandelmars)

<br/>

### Abstract

Many web services and other attacker-facing code bases are written in high-level scripting languages like JavaScript, Python, and Ruby.  By a construction, these languages prevent developers from introducing entire classes of bugs that plague low-level languages (e.g., buffer overflows, use-after-frees, and memory leaks).  Unfortunately, high-level languages alsointroduce new classes of severe, exploitable flaws that are often less obvious than low-level code bugs. These bugs lie in the runtime systems themselves, often in the *binding layer* that bridges the high-level language itself and the low-level language used to implement the runtime system.  In this talk, I will describe several classes of exploitable errors that plague the binding layer of JavaScript runtime systems, including Node.js and Chrome. We found over 80 exploitable bugs in these systems by developing a suite of easy-to-build static checkers using the new µchex framework.  The ease of writing such bug checkers -- a task I will demonstrate in this talk -- and the potential to impact hundreds of millions of people make language runtimes especially attractive attack vectors. As a step towards addressing these concerns and building more secure runtime systems, I will describe the design of a new binding-layer API for the JavaScript V8 engine.

### Bio

Deian is an Assistant Professor in the UCSD CSE Department. He is also the Chief Scientist at Intrinsic, a web security start-up he co-founded.  Deian's research interests span security, programming languages, and systems. He is particularly interested in building secure systems, such as browsers and language runtime systems, by applying programming language techniques and analysis.  He works on several secure systems, including SPAM, a secure package manager, COWL, a browser confinement system designed for modern web applications, Hails, a security-centric framework for building web platforms, LIO, a dynamic information flow control system, and ConstantC, a programming language for writing secure, constant-time code.  At Intrinsic, Deian is transferring some of his research into practice by building systems, tools, and languages that ultimately make it easier for developers to build and deploy Node.js web applications with minimal trust.  He is also a member of the W3C WebAppSec and the Node.js Security working groups, where he tries to make the web a safer place by working on specifications.  Deian completed his Ph.D.  in Computer Science at Stanford under David Mazières, John C. Mitchell, and Alejandro Russo. Prior to Stanford, he obtained a B.E. and M.E. in Electrical Engineering at the Cooper Union. At Cooper, he worked on GPU and FPGA crypto implementations.

