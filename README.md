# ChauBaoNguyenPhan-T1A1 Workbook

## `Q1. Identify and explain common and important components and concepts of web development markup languages`

***A markup language is a language used in web documents or applications (in industries such as vector graphics, content syndication or interface creation), that annotates text so that it may be manipulated by a computer.***

To distinguish themselves from text, most markup languages are human-readable, invisible to reader of a website or document, and can only be view by accessing the source code. They are also get read and rendered as opposed to programming’s executed unintelligible syntax.

Tags are used to define distinct elements across a markup language document. The tags are denoted by angle brackets (< and >), and whatever is contained between the tags is represented by formatted content. Depending on how it is used or its position in a document, markup can be either semantic or presentational.

Most markup languages are defined by an outside authority such as the W3C (World Wide Web Consortium) for use by a wide range of people. 

There are many markup languages but the most used for web development are:
* __HTML__ – Hypertext Markup Language (designed for displaying data)
* __XML__ – eXtensible Markup Language (designed for storing and transporting data)
* __XHTML__ – eXtensible Hypertext Markup Language (is a combination of HTML and XML)

## `Q2. Define the features of the following technologies that are essential in terms of the development of the internet:`

> Explain how each technology has contributed to the development of the internet.

## __Packets__ 

***Data such as email, images, video, etc. when sent from one IP to another IP over computer networks such as the internet get broken down into smaller fragments called packets.***

Each packets contains 1,000 - 1,500 bytes which includes:
* A header: includes IP addresses of the sender and receiver
* Data: the actual content, such as part of an image or a web page

These packets get sent off by the best available route as this makes the network more efficient. Once arrived at the allocated destination, these packets are then combined by the device that receives them. Other names of packets includes frame, block, cell, segment.

## __IP addresses (IPv4 and IPv6)__

***An IP (Internet Protocol) address is a numerical identification assigned to each device connected to a computer network that communicates using the IP protocol. An IP address serves as a unique identification for a single device on a network.***

An IP address is also known as an IP number or an Internet address, it serves the purpose of providing an address for devices to send and receive messages (aka. data) over computer networks such as the internet.

**Some differences between IPv4 vs IPv6:**

IPv4: 
* 32-Bit IP address
* Numerical addressing method
* Binary bits are separated by a dot (.)
	
IPv6:
* 128-Bit IP address
* Alphanumeric addressing method
* Binary bits are separated by a colon (:), also contains hexadecimal.

IPv4 is the fourth version of the Internet Protocol (IP), whereas IPv6 is the latest version. Hence, IPv6 is more advanced, secure, and faster than IPv4.

## __Routers and Routing__

***Routers are hardware devices developed with the main purpose of finding the most efficient path through which the IP packets can be transferred from source to destination across networks.***

It checks IP packet headers, including the destination address, and consults a table of known network. The table specifies which connections should be utilised as the next link to send each packet. 

***Routing is the process of selecting the best route for sending data packets and can be divided into two categories of static and dynamic.***

* Static: routes are set manually and must be corrected manually if there are changes in the networks

* Dynamic: routes are set by software according to the current state of the network and automatically updates if there are any changes to the networks

**Routers** and **routing** help improve the speed of sending and downloading data packets over the internet, making it more accessible for more people.

## __Domains and DNS__

***Domains also known as domain name, URL (Uniform Resource Locator), web address is an identifier that the internet users can use to find the location of a website.***

A **domain** could be linked to multiple IP addresses. A domain name can contain a minimum of 1 and a maximum of 63 characters.

***DNS (Domain Name System) helps computers talk to each other by converting a host name (i.e., www.google.com) to IP addresses such as 8.8.8.8.) adding efficiency and even security in the process, it's basically the internet's phonebook.***

**DNS** is managed by a non-profit organisation called internet Corporation for Assigned Names and Numbers (ICANN), which develops and executes the policies for domain names.

**Domains** and **DNS** helps make it much easier for internet users to access websites by enable them to lookup an IP address with a domain name rather than having to remember the IP address.

## `Q3. Define the features of the following technologies that are essential in terms of the development of the internet, and explain how each technology has contributed to the development of client and server communication over the internet (50 - 150 words for each technology):`

## __TCP__

***TCP (Transmission Control Protocol) is used in conjunction with IP and commonly referred to as TCP/IP suite as it's one of the main protocols of the Internet protocol suite.***

**TCP**'s main purpose is to check the packets sent from the server for errors, ask for packets to be resent, assembling them once arrived at the client's device and let he sender know whether the packets has been received successfully. It maintains a connection with the sender from the very beginning and end of this process, and *"a connection between client and server is established before data can be sent."* (Wikipedia, 2022)

## __HTTP and HTTPS__


***HTTP (Hypertext Transfer Protocol) is a method of data communication for the internet, it focuses on presenting the information but neglects on how the information is being transfer from one location to another.***

Data transfer using **HTTP** can be intercepted and manipulated by third parties, exposing both the information and the receiver of these information in danger.

***HTTPS is a similar but younger, more advanced, and more secure version of HTTP.***

The "S" stands for the word "Secure”, HTTPS originally uses SSL (Secure Sockets Layer) to move data, but it is now replaced by (TLS) Transport Layer Security (TLS) the *"security technology that establishes an encrypted connection between a web server and a browser.”* (Vukadinovic, 2018)

**HTTPS** helps secure data transfer between the client and server.

## __Web browsers (requests, rendering and developer tools)__

***A web brower is an application software that can be use by people around the world to access the World Wide Web via devices such as desktops, laptops, tablets, mobiles, etc.***

**Requests** are sent from the client to a server connected to the internet to retrieve information (data). The data is then transferred via HTTP and a piece of software known as a **rendering** engine is used to convert it into text and graphics. This information is written in Hypertext Markup Language (HTML), and web browsers process this code to display on our devices. **Developer tools** were created to help web developers with the main purpose of debugging code and testing user interface, they are part of an add-ons or built-in features of a web browser. (Wikipedia, 2022)

## `Q4. Identify THREE data structures used in the Ruby programming language and explain the reasons for using each.`

## __Arrays__

***Array is a data structure represents a collection of ordered, integer-indexed values (string, number, symbols, etc).***

Array positive index starts from 0 and negative index starts from -1. Arrays can be used to collect items, retrieve result from a loop and as the foundation for more complex data structure.

Example of what assigning values an Array looks like:

```
array_name = [value_1, value_2, value_3]
```

## __Hashes__

***Hash is another data structure that assigned a key for every value, so that the value can be looked up using the key.*** 

The key in a key/value pair can be anything (string, integer, symbol, etc.) and you can have as many key/value pairs as you need in a hash. These key/value pairs must be surrounded by curly braces { } and separated by commas (,).

Some uses of **Hash** includes naming and initialize objects, naming method arguments, counting characters in a string, find duplicates inside an array, mapping words to definitions, names to phone numbers, etc. (RubyGuides, 2022)

Example of what an old Hash syntax uses symbols as keys looks like:
```
{:one => "value_1", :two => "value_2", :three => "value_3"}
```

Example of what a new Hash syntax uses symbols as keys looks like:
```
{one: "value_1", two: "value_2", three: "value_3"}
```

## __Trie__

***Trie (aka. digital tree or prefix tree) is a tree data structure used for locating keys inside a set.***

*“These keys are most often strings, with links between nodes defined not by the entire key, but by individual characters”* (Wikipedia, 2022). It's useful for working with words, swiftly looking for terms that begin with a prefix or searching for the entire word; and it’s commonly used in word games, spelling checkers and auto complete suggestions. (RubyGuides, 2022)

## `Q5. Describe the features of interpreters and compilers and how they are different.`

## __Interpreters__

Interpreter is a computer program that converts the source code to machine code, and often offer features such as dynamic typing and smaller program size.

## __Compilers__

Compiler is a translator that takes inputs from high level programming language (C, C++, Java, etc.) and produces outputs in machine or assembly language (binary 1 & 0) that the processor can execute. Compilers checks for error, range, limits, etc.

**Differences between Interpreters and Compilers are:**

Interpreters:
* Translate one statement at a time
* Take less time to analyse source code but more time to execute
* Used by Ruby, JavaScript, Python, etc.

Compilers:
* Scan the entire document and then translate
* Take more time to analyse source code but less time to execute
* Used by C, C++, Java, etc.

## `Q6. Identify TWO commonly used programming languages and explain the benefits and drawbacks of each.`

## __Ruby__

### Pros:

* One of the most time-efficient languages in developing software (when using in combination with the Rails framework)
* Well developed and highly active community
* Can be integrated easily with frontend frameworks
* Considered to be very secure in combination with the Rails framework
* Easy to write, read and understand

### Cons:

* Speed of application might be a concern when developing applications for a large user base
* Still seen as a niche language and usually not the first choice for back-end developers
* Less flexibility compares to other languages
* Can be difficult to debug

## __JavaScript__

### Pros:

* Great for developing interactive websites and mobile application development
* Wide variety of add-ons
* Easy to learn and understand
* Supported by all modern browsers

### Cons:

* Different browser interprets JavaScript differently
* Client-side security can be compromised
* Only supports single inheritance

## `Q7. Identify TWO ethical issues from the areas below and discuss the extent to which an IT professional is ethically responsible in terms of the issue.`

> ### List of topics containing ethical issues:
>
> - access to a user’s personal information (medical, family, financial, personal attributes such as sexuality, religion, or beliefs)
> - intellectual property, copyright, and acknowledgement.
> - criminal acts such as theft, fraud, trafficking and distribution of prohibited substances, terrorism
> - GPS tracking data and other types of metadata, MAC addresses, hardware fingerprints
> - freedom of thought, conscience, speech and the media
> - aggressive sales and marketing practices designed to mislead and deceive consumers
> - trading of shares on the stock exchange OR crypto-currencies
>
> ### For each ethical issue identify a source of legal information relating to the ethical issue and discuss whether the law is helpful in assisting a developer to act in an ethical way. (Word count guide: 200 words max)
>
> ### Conduct research into a case study of ONE of the ethical issues you have chosen discuss how an ethical IT professional should respond to the case study and how they might mitigate or prevent ethical breaches. (Word count guide: 400 - 600 words)

## `Q8. Explain control flow, using examples from the Ruby programming language`

Control flow is the order in which statements, instructions or function calls are executed or evaluated, based on whether a particular condition was met.

### Control flow examples:

__If/else statements:__

Starts at the key word ```if``` and ends at the key word ```end```. If the the condition is met, ```if``` statement block will execute; otherwise ```else``` statement block will execute instead.
```
puts "What's the weather today?"
temp = gets.to_i

if temp < 15
    puts "It's too cold"
elsif temp >= 15 && temp <= 28
    puts "It's beautiful today"
elsif temp > 28
    puts "It's too hot"
end
```

__Case statements:__

Starts with the key word ```case``` and follows with a variable. ```when``` statements executes when condition/s matches the variable, otherwise ```else``` case will execute.

```
case time
when 7..11
    puts "Good morning!"
when 12
    puts "Lunchtime"
when 13..18
    puts "Afternoon blues"
when 19, 20
    puts "Dinnertime"
when 21..23, 0..5
    puts "Sleepy time"
else
    puts "That is not correct 24hr time!"
end
```

__Ternary operators:__

Shorthand for if else statements, involves ```?``` and ```:``` and best for when both ```if``` and ```else``` are to be executed in one line of code .

```
puts "How old are you?"
age = gets.chomp.to_i

puts "Are you a citizen?"
citizen = gets.chomp

puts age>=18 && citizen=="yes" ? "You are eligible to vote!" : "You are ineligible to vote!";
```

## `Q9. Explain type coercion`

Type coercion (also known as implicite type conversion) is an automatic type conversion by the compiler and one of the many ways of altering an expression from one data type to another along with its value. Some methods of type coercion are ```.to_int```, ```.to_str```, etc.



## `Q10. Explain data types, using examples`

| Data Type | Description                                                                                                                                                     | Example                                                                                                                                                    |
|-----------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Numbers   | This data types only accept numeric variables, defined by digits and uses a dot for decimal. Integer and Float are two most common type of Numbers.             | Integer: month = 12  Float: weight: 52.50                                                                                                                  |
| Strings   | String/s of connected letters which represents a word or sentence, encapsulated in single ('') or double ("") quotation marks.                                  | greeting = "Hello World!"                                                                                                                                  |
| Boolean   | Only True or False value can be added to this data type and it only requires 1 bit of memory.                                                                   | morning = true if morning puts "Good morning!" else puts "Hello!" end                                                                                      |
| Arrays    | Stores any type of data or list of data, separated by commas (,) and captured inside square [] brackets. In any array, 0 is the starting position for elements) | month = [january, february, march] puts month(1)                                                                                                           |
| Hashes    | Stores any kind of data in key/value pairs, can be used to look up a value using a key, contained inside curly {} brackets and separated by commas (,).         | memberDetails = { "name" => "Jenny" , "age" => "26" , "city" => "Melbourne" } memberDetails.each.do \|key, value\| puts "The member's #{key} is #{value}." |
| Symbols   | Symbols are more light weight (take less memory than a string) which is why they are often used instead of strings, a colon (:) is the start of a symbol.       | date = { :year => "2022" , :month => "March" , :day => 19 } puts date[:year] puts date[:month] puts date[:day]                                             |

## `Q11. Here’s the problem: “There is a restaurant serving a variety of food. The customers want to be able to buy food of their choice. All the staff just quit, how can you build an app to replace them?”`

> - Identify the classes you would use to solve the problem
> - Write a short explanation of why you would use the classes you have identified

## `Q12. Identify and explain the error in the code snippet below that is preventing correct execution of the program`

```
celsius = gets
fahrenheit = (celsius * 9 / 5) + 32
print "The result is:"
print fahrenheit
puts "."
```
The code above does not work because variable `celsius` is assigned to `gets` user's input but there was no promt to ask for their input.

`gets` also needs to convert the input to integer or else Ruby will try to calculate `celsius` as a string in a mathematical equation which will result in an error. The last 3 lines of code can be simplified using the "string interpolation" method.

**The adjusted code:**
```
puts "What is celsius temperature that you would like to convert to fahrenheit?"
celsius = gets.chomp.to_i
fahrenheit = (celsius * 9 / 5) + 32
puts "The temperature in fahrenheit is: #{fahrenheit}."
```

## `Q13. The code snippet below looks for the first two elements that are out of order and swaps them; however, it is not producing the correct results. Rewrite the code so that it works correctly.`

```
arr = [5, 22, 29, 39, 19, 51, 78, 96, 84]
i = 0
while (i < arr.size - 1 and arr[i] < arr[i + 1])
    i = i + 1 end
puts i
    arr[i] = arr[i + 1]
    arr[i + 1] = arr[i]
```

## `Q14. Demonstrate your algorithmic thinking through completing the following two tasks, in order:`

> 1. Create a flowchart to outline the steps for listing all prime numbers between 1 and 100 (inclusive). Your flowchart should make use of standard conventions for flowcharts to indicate processes, tasks, actions, or operations

> 2. Write pseudocode for the process outlined in your flowchart

## `Q15. Write pseudocode OR Ruby code for the following problem:`

> You have access to two variables: raining (boolean) and temperature (integer). If it’s raining and the temperature is less than 15 degrees, print to the screen “It’s wet and cold”, if it is less than 15 but not raining print “It’s not raining but cold”. If it’s greater than or equal to 15 but not raining print “It’s warm but not raining”, and otherwise tell them “It’s warm and raining”.

## `Q16. ACME Corporation are hiring a new junior developer, as part of their hiring criteria they've created a "coding skill score" based on the specific competencies they require for this role; the more important the skill is for ACME corp, the more points it contributes to the "coding skill score" The skills are weighted as follows:`
>
> - Python (1)
> - Ruby (2)
> - Bash (4)
> - Git (8)
> - HTML (16)
> - TDD (32)
> - CSS (64)
> - JavaScript (128)
​
> ### Write a program that allows a user to input their skills and then tells them 
>
> a) Their overall "coding skill score" 
> b) Skills they may want to learn, and how much each one would improve their score

# References

## Markup Languages

* Amelia WordPress Booking Plugin. 2019. Markup Languages: What They’re All About. [ONLINE] Available at: https://wpamelia.com/markup-languages/. [Accessed 14 March 2022].
* ThoughtCo. 2021. What Are Markup Languages? — Web Design. [ONLINE] Available at: https://www.thoughtco.com/what-are-markup-languages-3468655. [Accessed 14 March 2022].
* Erika Varagouli. 2021. What Each Markup Language Is Used For. [ONLINE] Available at: https://www.semrush.com/blog/markup-language/.  [Accessed 14 March 2022].
* Markup Language: What it is and how it works - Seobility Wiki. 2022. Markup Language: What it is and how it works - Seobility Wiki. [ONLINE] Available at: https://www.seobility.net/en/wiki/Markup_Language. [Accessed 14 March 2022].

## Packets

* Khan Academy. 2022. IP packets (article) | The Internet | Khan Academy. 
[ONLINE] Available at: https://www.khanacademy.org/computing/computers-and-internet/xcae6f4a7ff015e7d:the-internet/xcae6f4a7ff015e7d:routing-with-redundancy/a/ip-packets. [Accessed 15 March 2022].
* SearchNetworking. 2022. What are network packets and how do they work?. [ONLINE] Available at: https://www.techtarget.com/searchnetworking/definition/packet. [Accessed 15 March 2022].
* Cloudflare. 2022. What is a packet? | Network packet definition. [ONLINE] Available at: https://www.cloudflare.com/en-au/learning/network-layer/what-is-a-packet/. [Accessed 15 March 2022].
* HowStuffWorks. 2021. What is a network packet? | HowStuffWorks. [ONLINE] Available at: https://computer.howstuffworks.com/question525.htm. [Accessed 16 March 2022].

## IP addreses (IPv4 and IPv6)

* Wikipedia. 2022. IP address - Wikipedia. [ONLINE] Available at: https://en.wikipedia.org/wiki/IP_address. [Accessed 15 March 2022].
* FutureLearn. 2022. IP Packets, Routers and Routing. [ONLINE] Available at: https://www.futurelearn.com/info/courses/introduction-to-networking/0/steps/53448. [Accessed 15 March 2022].

## Routers and Routing

* Lesics. 2019. Understanding Routing! | ICT#8 - YouTube. [ONLINE] Available at: https://www.youtube.com/watch?v=gQtgtKtvRdo. [Accessed 15 March 2022].
* Wikipedia. 2022. Routing - Wikipedia. [ONLINE] Available at: https://en.wikipedia.org/wiki/Routing. [Accessed 15 March 2022].
* Cloudflare. 2022. What is routing? | IP routing. [ONLINE] Available at: https://www.cloudflare.com/en-au/learning/network-layer/what-is-routing/. [Accessed 16 March 2022].

## Domains and DNS

* What is a Domain?. 2017. What is a Domain?. [ONLINE] Available at: https://www.computerhope.com/jargon/d/domain.htm. [Accessed 16 March 2022].
* Squarespace. 2017. What is a Domain? - YouTube. [ONLINE] Available at: https://www.youtube.com/watch?v=TqdEvlvbmt4. [Accessed 16 March 2022].
* wpbeginner. 2021. Beginner’s Guide: What is a Domain Name and How Do Domains Work?. [ONLINE] Available at: https://www.wpbeginner.com/beginners-guide/beginners-guide-what-is-a-domain-name-and-how-do-domains-work/. [Accessed 16 March 2022].
* Amazon Web Services. 2016. What is DNS? - Introduction to Domain Name System - YouTube. [ONLINE] Available at: https://www.youtube.com/watch?v=e2xLV7pCOLI&t=11s. [Accessed 16 March 2022].
* Cloudflare. 2022. What is DNS? | How DNS works. [ONLINE] Available at: https://www.cloudflare.com/en-au/learning/dns/what-is-dns/. [Accessed 16 March 2022].
* Keith Shaw and Josh Fruhlinger. 2020. What is DNS and how does it work? | Network World. [ONLINE] Available at: https://www.networkworld.com/article/3268449/what-is-dns-and-how-does-it-work.html. [Accessed 16 March 2022].
* Amazon Web Services, Inc.. 2022. What is DNS? – Introduction to DNS - AWS. [ONLINE] Available at: https://aws.amazon.com/route53/what-is-dns/. [Accessed 16 March 2022].

## TCP

* Cloudflare. 2022. What is TCP/IP?. [ONLINE] Available at: https://www.cloudflare.com/en-au/learning/ddos/glossary/tcp-ip/. [Accessed 16 March 2022].
* Khan Academy. 2022. Transmission Control Protocol (TCP) (article) | Khan Academy. [ONLINE] Available at: https://www.khanacademy.org/computing/computers-and-internet/xcae6f4a7ff015e7d:the-internet/xcae6f4a7ff015e7d:transporting-packets/a/transmission-control-protocol--tcp. [Accessed 16 March 2022].
* OpenClassrooms. 2022. Understand TCP: clients, servers, ports, and sockets - Handle Web Requests With Ruby - OpenClassrooms . [ONLINE] Available at: https://openclassrooms.com/en/courses/4924041-handle-web-requests-with-ruby/5274816-understand-tcp-clients-servers-ports-and-sockets. [Accessed 16 March 2022].
* Wikipedia. 2022. Transmission Control Protocol - Wikipedia. [ONLINE] Available at: https://en.wikipedia.org/wiki/Transmission_Control_Protocol. [Accessed 16 March 2022].

## HTTP and HTTPS

* GlobalSign GMO Internet, Inc.. 2018. What's the difference between HTTP and HTTPS?. [ONLINE] Available at: https://www.globalsign.com/en/blog/the-difference-between-http-and-https. [Accessed 16 March 2022].
* firstsiteguide.com. 2022. No page title. [ONLINE] Available at: https://firstsiteguide.com/wp-content/uploads/2016/11/http-vs-https-main-image.jpg. [Accessed 16 March 2022].
* Wikipedia. 2022. HTTPS - Wikipedia. [ONLINE] Available at: https://en.wikipedia.org/wiki/HTTPS. [Accessed 16 March 2022].

## Web browsers (requests, rendering and developer tools)

* Wikipedia. 2022. Web browser - Wikipedia. [ONLINE] Available at: https://en.wikipedia.org/wiki/Web_browser. [Accessed 16 March 2022].
* Mozilla. 2022. What is a web browser?. [ONLINE] Available at: https://www.mozilla.org/en-US/firefox/browsers/what-is-a-browser/. [Accessed 16 March 2022].
* Wikipedia. 2022. Web development tools - Wikipedia. [ONLINE] Available at: https://en.wikipedia.org/wiki/Web_development_tools. [Accessed 16 March 2022].

## Ruby's Data Structures

* RubyGuides. 2019. An Overview of Data Structures For Ruby Developers - RubyGuides. [ONLINE] Available at: https://www.rubyguides.com/2019/04/ruby-data-structures/. [Accessed 15 March 2022].
* GeeksforGeeks. 2021. Ruby | Arrays - GeeksforGeeks. [ONLINE] Available at: https://www.geeksforgeeks.org/ruby-arrays/. [Accessed 17 March 2022].
* How To Work with Arrays in Ruby | DigitalOcean. 2017. How To Work with Arrays in Ruby | DigitalOcean. [ONLINE] Available at: https://www.digitalocean.com/community/tutorials/how-to-work-with-arrays-in-ruby. [Accessed 17 March 2022].
* Ruby - Arrays. 2022. Ruby - Arrays. [ONLINE] Available at: https://www.tutorialspoint.com/ruby/ruby_arrays.htm. [Accessed 17 March 2022].
* ruby-doc.org. 2022. No page title. [ONLINE] Available at: https://ruby-doc.org/core-3.1.1/Hash.html. [Accessed 17 March 2022].
* Ruby - Hashes. 2022. Ruby - Hashes. [ONLINE] Available at: https://www.tutorialspoint.com/ruby/ruby_hashes.htm. [Accessed 17 March 2022].
* Ruby Hashes - A Detailed Guide. 2022. Ruby Hashes - A Detailed Guide. [ONLINE] Available at: https://launchschool.com/books/ruby/read/hashes. [Accessed 17 March 2022].
* Hashes | Ruby for Beginners. 2022. Hashes | Ruby for Beginners. [ONLINE] Available at: http://ruby-for-beginners.rubymonstas.org/built_in_classes/hashes.html. [Accessed 17 March 2022].
* Wikipedia. 2022. Trie - Wikipedia. [ONLINE] Available at: https://en.wikipedia.org/wiki/Trie. [Accessed 17 March 2022].

## Interpreter and Compiler

* freeCodeCamp.org. 2020. Interpreted vs Compiled Programming Languages: What's the Difference?. [ONLINE] Available at: https://www.freecodecamp.org/news/compiled-versus-interpreted-languages/. [Accessed 17 March 2022].
* Business Insider. 2019. Difference Between Compiler And Interpreter. [ONLINE] Available at: https://www.businessinsider.in/difference-between-compiler-and-interpreter/articleshow/69523408.cms. [Accessed 17 March 2022].
* Interpreter Vs Compiler : Differences Between Interpreter and Compiler. 2022. Interpreter Vs Compiler : Differences Between Interpreter and Compiler. [ONLINE] Available at: https://www.programiz.com/article/difference-compiler-interpreter. [Accessed 17 March 2022].
* Guru99. 2022. Compiler Vs. Interpreter: What’s the Difference?. [ONLINE] Available at: https://www.guru99.com/difference-compiler-vs-interpreter.html. [Accessed 17 March 2022].
* GeeksforGeeks. 2021. Difference between Compiler and Interpreter - GeeksforGeeks. [ONLINE] Available at: https://www.geeksforgeeks.org/difference-between-compiler-and-interpreter/. [Accessed 17 March 2022].

## Ruby & JavaScript

* Pros and cons of Ruby software development | The Codest. 2020. Pros and cons of Ruby software development | The Codest. [ONLINE] Available at: https://thecodest.co/blog/pros-and-cons-of-ruby-software-development/. [Accessed 17 March 2022].
* code-club. 2021. Ruby program 2020 - Features, Advantages and Disadvantages. [ONLINE] Available at: https://code-mentor.org/ruby-program-advantages-and-disadvantages/. [Accessed 17 March 2022].
* Northeastern University Graduate Programs. 2020. The 10 Most Popular Programming Languages to Learn in 2022. [ONLINE] Available at: https://www.northeastern.edu/graduate/blog/most-popular-programming-languages/. [Accessed 17 March 2022].
* Data Flair. 2022. Pros and Cons of JavaScript – Weigh them and Choose wisely!. [ONLINE] Available at: https://data-flair.training/blogs/advantages-disadvantages-javascript/. [Accessed 17 March 2022].

## Control FLow

* Nayak N, 2020, Control Flow, Academy of Information Technology
* Wikipedia. 2022. Control flow - Wikipedia. [ONLINE] Available at: https://en.wikipedia.org/wiki/Control_flow. [Accessed 18 March 2022].
* Control flow - MDN Web Docs Glossary: Definitions of Web-related terms | MDN. 2022. Control flow - MDN Web Docs Glossary: Definitions of Web-related terms | MDN. [ONLINE] Available at: https://developer.mozilla.org/en-US/docs/Glossary/Control_flow. [Accessed 18 March 2022].
* 

## Data Types
* GeeksforGeeks. 2019. Ruby | Data Types - GeeksforGeeks. [ONLINE] Available at: https://www.geeksforgeeks.org/ruby-data-types/. [Accessed 18 March 2022].
* Built-In Data Types | Ruby for Beginners. 2022. Built-In Data Types | Ruby for Beginners. [ONLINE] Available at: http://ruby-for-beginners.rubymonstas.org/built_in_classes.html. [Accessed 18 March 2022].
* EDUCBA. 2022. Ruby Data Types | Top 7 Ruby Data Types with Examples. [ONLINE] Available at: https://www.educba.com/ruby-data-types/. [Accessed 18 March 2022].
