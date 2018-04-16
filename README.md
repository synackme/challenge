# Challenge Lab 2 - Custom Protocol

At the following URL, you'll find a very small web application:

http://ec2-54-146-39-72.compute-1.amazonaws.com:4567/

U - "\*\*\*redacted\*\*\*" P - "\*\*\*redacted\*\*\*".

This application is a front-end testing interface to a trading system. ***THE WEB APPLICATION IS NOT IN SCOPE***. 

We have already tested you on web application vulnerabilities this is something completely different. The ==underlying protocol== is what we want tested here. This means you will ==need some way of intercepting the communication between the trading client and the backend==.

## Basic terms & conditions:

* The only thing we know about the application is it's a trading system, with a **custom protocol**, and we've been given this very simple QA application to verify it's running.
* THE WEB APPLICATION IS OUT OF SCOPE. Feel free to use it anyway you see fit, but don't waste time finding vulnerabilities.
* **The web front end talks to the backend service (indicated by the hostname and port in the UI). It is the communication protocol that interacts with the backend service we want you to evaluate. How you manipulate that traffic is up to you.**

	
Take as much time as needed, but don't kill yourself. Use your own judgement when to stop. This challenge will probably take slightly longer than the web challenge, and will probably require small amounts of code. The same caveats as the web test apply here. The trading system likely has multiple features; you should be testing each one.

## Please make sure you give us:

* A summary of the protocol format. 
* A severity level for everything.
* Impact of the issues discovered, i.e. what this really means, and how it can be used
* A recommendation on how to fix it. This does not need to be a fully fleshed out plan, just a sentence or two on the underlying cause and how we could fix it.
* You can use whichever tools you like.

