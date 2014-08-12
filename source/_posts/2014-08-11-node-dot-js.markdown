---
layout: post
title: "Node.js"
date: 2014-08-11 21:49:31 -0400
comments: true
categories: Flatiron School
---
Yesterday at The Flatiron School, my group came up with an idea for an app for project mode. We wanted to show a world map and display live streaming, trending tweets over each country in order to help people visualize what is going on all over the world. In order to do this, however, we wanted the tweets to be streamed continuously. Therefore, for the project, my group decided to learn Node.js.

What is Node?


Node is not a replacement for a web framework such as Rails. Rather, it is a platform that allows you to build scalable network applications using JavaScript on the server-side.


What is special about Node?


Node uses non-blocking code. This is unique because let's say you had two files. With blocking code, it would read one file and then the next file. With non-blocking code, on the other hand, we can read two files at the same time, in parallel. Thus, Node is perfect for our project, as it allows us to read a large number of tweets simultaneously.


Events


Node uses an event-driven model. To understand the positive implications of an event-driven model, as opposed to a thread-based system, Dan York uses the analogy of standing in line at a doctor's office to see the receptionist. In a threat-based system, when you get to the receptionist, you stand at the counter for as long as it takes you to complete your transaction. If you have to fill out multiple forms, you do so while the receptionist sits there waiting for you. "You are blocking him or her from servicing any other customers." In an event-driven model, like Node, you are given the forms, and you fill them out elsewhere while the receptionist helps the next person in line. In Node, the web server accepts a request, hands it off to be handled, and goes on to deal with the next web request. Examples of events include request, connection and close. Thus, in Node, two requests can occur simultaneously and no code will be blocked.



Node Package Manager (NPM)
NMP is a central repository where people can publish their modules and you can install them. It is similar to Ruby Gems.



Express


Express is a Sinatra inspired web development framework for Node.js.




Sources:
http://code.danyork.com/2011/01/25/node-js-doctors-offices-and-fast-food-restaurants-understanding-event-driven-programming/
https://www.codeschool.com/courses/real-time-web-with-node-js