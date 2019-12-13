# T1A1 - WORKBOOK
#### By David Johnson

# QUESTION 1
Five key events from 1980 onwards:

#### 1. Creation of the Domain Name System (DNS)

DNS was invented by Paul Mockapetris, with the original specifications published by the Internet Engineering Task Force in November 1983.  

DNS is considered to be the backbone of the internet as we know it - a decentralized and hierarchical naming system that connects URLs with their IP addresses,  making it possible to type words into a browser instead of a string of numbers.  

There were seven “top-level” domain names created - gov, edu, com, net, org, mil and int.


#### 2 The Protocol Wars
Although there was always a common goal of building a global computer network, this could only happen if everyone was using the same Internet Protocol (IP) - which is the method by which data is sent from one computer to another.  

By the early 1980’s there were several competing systems - Europe was using OSI (Open Systems Intercoonect) and the United States were using the Internet/Arpanet protocol (switching from NCP to TCP/IP in January 1983). 

There were also several prominant contenders from the private sector: 
 - IBM's SNA
 - DEC's DECNET
 - Apple's APPLETALK
 - Banyan Vines
 - Novell's IPX

The TCP/IP model eventually won out and is now the dominant protocol suite that is used on today’s Internet.  It is named from the two most important protocols contained within - the Transmission Control Protocol (TCP) and the Internet Protocol (IP),

#### Introduction of the World Wide Web (WWW)

The World Wide Web was invented by British Scientist Tim Berners-Lee in 1989 while he was working at CERN and is an information system that allows documents to connect through hypertext links.

It was originally called “Mesh” and was proposed to persuade CERN that a global hypertext system was not only in CERN’s best interest but was needed to meet the demand for automated information-sharing between scientists in universities and institutes around the world.  

The World Wide Web was launched to the public on August 6 1991.

#### The First Graphical Web Browser 

Until the early 1990’s the internet was used primarily by the government, academics and technology geeks. Although there were already web browsers available, it wasn’t until the introduction of Mosaic in 1993 that the internet became accessible to non-technical people.

Primitive web pages were nothing more than interactive word documents but became instantly popular.  This, combined with the power of emails, allowed people to start understanding the enormous possibilities that came with a large interconnected network.  

#### Commercialization of the Internet

Although there were already commercial enterprises in existence, it wasn’t until 1995 that the internet was first considered to be truly commercialized.  This was due, in part to the development of SSL encryption (Secure Sockets Layer) which allowed for safe financial transactions. It was also the year two major companies were started – the Echo Bay (now EBAY) and Amazon.

The introduction of https (the hypertext transfer protocol encrypted with SSL) as well as user-friendly web browsers and major internet service providers contributed to the dot com boom of the late 1990's.

# QUESTION 2

#### Packets

Packets allow large pieces of information to be transferred accross the TCP/IP network by breaking the data down into smaller pieces or "packets" in order to be compiled again at the other end .  This technology was of critical importance in the development of the internet as it allows for different bandwidths and potential interference while tranferring data from one IP address to another.

#### IP Addresses (IPv4 and IPv6)

IP (internet protocol) addresses are the “digital addresses” used by computers/digital devices - each device has a unique IP address.  This is important because you first need to be able to locate and differentiate between devices before being able to send and receive information.

The common type of IP address is known as IPv4, for "version 4" which uses a 32-bit address space and supports a maximum of 4.3 billion unique IP addresses.

The IPv6 address was later created which consists of eight groups of four hexadecimal digits so theoretically this will never run out of unique addresses.

#### Routers and Routing

A router is a device that relays data packets between computer networks. The process of routing involves assessing a packet received from one host and directing it to the next network.  In order to determine which interface the packet should be forwarded to, routers use routing policies or routing tables (a list of known routes). 

#### Domains and DNS

A domain is a collection of internet addresses that share a common suffix, or under the control of a particular organization or individual. DNS (Domain Name System) is the global database that connects IP addresses with their corresponding domain names. This has greatly helped the internet's usability as it allows users to enter familiar words instead of complex numbers.

# QUESTION 3

#### TCP
TCP (Transmission Control Protocol) is the standard that defines how data is exchanged using the TCP/IP model. 
  
This technology has contributed to the advancement of client and server communication because it is connection oriented, reliable, provides end-to-end communication and ensures the data reaches it’s destination in the same order it was sent. 

#### HTTP and HTTPS

HTTP (HyperText Transfer Protocol) defines how messages are formatted and transmitted and also defines what actions web servers and browsers should take in response.  HTTP is connectionless, media independent and stateless.  

HTTPS is the secure version of HTTP which utilises a SSL/TLS encryption.

This technology contributed to the development of client and server communication by allowing files, images and videos to be carried to devices.  


#### Web Browswers (requests, rendering and developer tools)

A web browser is a program that allows users to view web pages on the internet by translating HTTP into readable content, thus contributing to the development of client and server communication over the internet.  There are a multitude of different browsers available for each operating system, all with their own features.  
The client (browser) submits a HTTP request to the server, which then returns a response to the client. The response contains status information about the request and may also contain the requested content.

The browser then uses a rendering engine to render and display the requested content.  By default the rendering engine can display HTML and XML documents and images.

Modern web browsers also include their own developer tools.  These tools do a range of things, from inspecting currently-loaded HTML, CSS and JavaScript to showing which assets the page has requested and how long they took to load. 

# QUESTION 4

#### Arrays

If you want to save a range of numbers, or pack multiple values into one variable, then you use the data structure called an array. Arrays are commonly used in computer programs to organize data so that a related set of values can be easily sorted or searched.
Data inside an array does not have to be in any order, and arrays can hold any type of data, whether it be a string, an integer, booleans, objects, even additional arrays.

#### Hashes

Hashes are a collection of key-value pairs. They are also known as maps because they map keys (names) to values. Hashing is used to index and retrieve items in a database because it is faster to find the item using the shorter hashed key than to find it using the original value.  Hashing is a more reliable and flexible method of data retrieval than any other data structure

#### Blocks

Blocks are one of the only things in Ruby that is not an object. They are basically a set of instructions associated with a method call. While the method runs, it can invoke the block one or more times. By utilizing blocks you can reduce repetition and even make coding less error-prone.  

# QUESTION 5

A **COMPILER** converts the whole program into intermediate object code in one go.  Once a program is compiled, its source code is not needed for running the code. In general, compiled programs run faster than the interpreted programs however, the memory requirement is greater due to the creation of the object code.  Errors are displayed after compilation, all at the same time which makes error detection difficult. 

An **INTERPRETER** imitates the execution of programs written in a source language and converts the program by taking a single line at a time, this source code is required to run the program every time. In general, interpreted programs run slower than compiled programs. Interpreter’s require less memory as it does not create intermediate object code and as interpreter's display the errors of each line one by one, it makes error detection easier compared to compilers. 

#### QUESTION 6

#### RUBY
BENEFITS: Ruby is an eloquent and succinct language.  It has great tooling, high quality code libraries (there’s a gem for just about anything) and a pragmatic approach to software.  The Ruby community is large and full of high calibre engineers who favour responsible development and promote testing and test automation.  Ruby on Rails is extremely popular in Silicon Valley with the likes of Airbnb, Etsy, GitHub & Shopify all using Ruby on Rails

DRAWBAKCS: 
One of the biggest argument against Ruby on Rails is it’s slow runtime speed as well as the boot speed of the Rails framework. Depending on the number of gem dependencies and files, it can take a significant amount of time to start, which can frustrate and hinder developer performance. It can also be hard to find good documentation and resources online for the less popular gems and for libraries which make heavy use of mixins. 

#### PHP

BENEFITS: It’s flexible mature language with a small learning curve. There are lots of libraries, packages and frameworks available for free and great community support. PHP is extremely popular – much of the web uses PHP as the back end and therefore there are always jobs available for those who can not only create code but also maintenance. PHP has first-class debugging and questions easily answered because chances are someone’s done something similar already.  

DRAWBACKS:
Because it’s interpreted and not compiled, performance is not necessarily as good as other languages.  Another issues is because it’s flexible and forgiving it becomes really easy to write bad PHP and also has quite a few inconsistently named functions.  Due to the low learning curve/low barrier of entry, the outside world tends to view PHP as an insecure and entry level language which can affect ability to secure higher paying jobs.  PHP is also rarely used in emerging technologies or process development. Due to threaded execution and the need for global extensions there are also scalability and support issues. 

#### QUESTION 7

Identify TWO ethical issues from the areas below and discuss the extent to which an IT professional is ethically responsible in terms of the issue.

For each ethical issue identify a source of legal information relating to the ethical issue and discuss whether the law is helpful in assisting a developer to act in an ethical way.

 - criminal acts such as theft, fraud, trafficking and distribution of prohibited substances, terrorism

- aggressive sales and marketing practices designed to mislead and deceive consumers

Conduct research into a case study of ONE of the ethical issues you have chosen discuss how an ethical IT professional should respond to the case study and how they might mitigate or prevent ethical breaches.	

An interesting case study is Silk Road - and online platform.  An IT professional should 

    200 - 400 words for each ethical issue

#### QUESTION 8

Control flow is the order that methods, instructions, and statements are evaluated and executed when a program is running. A good example of this from the Ruby programming language is an if/elsif/else statement: 

``` ruby
puts "enter a number 1-10: "
answer = gets.chomp
answer = answer.to_i;

if answer == 1
  puts "number is 1"
elsif answer == 5
  puts "number is 5"
elsif answer == 10
  puts "number is 10"
else
  puts "number is something other than 1, 5, or 10"
end

  ```
In the code above, the user is asked to provide a number from 1-10.  Once the number is entered and changed into an integer, ruby then executes the if statement from top to bottom.  

If the chosen number is "1", it will print "number is 1" and then stop running. If the number is something else, it will then move onto the first elsif which will checks if the number is "5".  If so it prints and stops, if not it then moves onto the next elsif.  If the number does not match 1, 5, or 10 it then moves to the else statement.  This is an example of control flow.  

# QUESTION 9

Type coercion is the changing of an object's type into another type, together with its value eg. changing a float into an integer, or an integer into a string.

``` ruby
puts "enter a number 1-10:"
answer = gets.chomp
answer = answer.to_i; 
```
In the example from above, when the number is entered by the user it is automatically a string and would need to be changed to an integer to be able to excecute the if/elsif/else statement.  By using the ".to_i" this successfully changes the string into an integer.  

# QUESTION 10

**Boolean:** is a data type that represents only true or false. There is no Boolean class in Ruby.
```ruby
y = false
```
**Symbols:** are like strings but used instead of strings because they can take up much less memory. These belong to class *Symbol*:
```ruby
x = :symbol
```
**Numbers:** Generally a number is defined as a series of digits, using a dot as a decimal mark. 

*Integers* are whole numbers.  These belong to class *Integer*: 
```ruby
puts 15
```
Floating point numbers or *floats* contain decimal points. These belong to class *Float*:
```ruby
puts 15.4596
```
**Strings:** are a group of letters that represent a sentence or a word. These belong to class *String*:

```ruby
puts "this is a string"
```

**Arrays:** store data or list of data. These belong to class *Array*:
```ruby
x = [1,2,3,4,5,6,7,8,9,10]
```

**Hashes:** assign values to keys. These belong to class *Hash*:
```ruby
numbers = {100 => "A", 200 => "B", 300 => "C"}"
```


#### QUESTION 11

Here’s the problem: “There is a restaurant serving a variety of food. The customers want to be able to buy food of their choice. All the staff just quit, how can you build an app to replace them?”>
- Identify the classes you would use to solve the problem
- Write a short explanation of why you would use the classes you have identified	
    
100

#### QUESTION 12

Identify and explain the error in the following code that is preventing correct execution of the program


``` ruby
celsius = gets
fahrenheit = (celsius * 9 / 5) + 32
print "The result is: "
print fahrenheit
puts "."
  ```

#### QUESTION 13

**just need to swap 39 and 19 around
1. declaring array
2. index of array
3. conditions of loop
4. counting loop and ending
5. outputs index
6. this is wehre its supposed to swap - causing it to eliminate swapped number (need to save it somehow)


The following code looks for the first two elements that are out of order and swaps them; however, it is not producing the correct results. Rewrite the code so that it works correctly.

``` ruby
arr = [5, 22, 29, 39, 19, 51, 78, 96, 84]
i = 0
while (i < arr.size - 1 and arr[i] < arr[i + 1])
  i = i + 1 end
puts i
arr[i] = arr[i + 1]
arr[i + 1] = arr[i]
 ```

#### QUESTION 14
Demonstrate your algorithmic thinking through completing the following two tasks, in order:
  i. Create a flowchart to outline the steps for listing all prime numbers between 1 and 100 (inclusive). Your flowchart should make use of standard conventions for flowcharts to indicate processes, tasks, actions, or operations  
ii. Write pseudocode for the process outlined in your flowchart

#### QUESTION 15

Write pseudocode OR Ruby code for the following problem:

You have access to two variables: raining (boolean) and temperature (integer). If it’s raining and the temperature is less than 15 degrees, print to the screen “It’s wet and cold”, if it is less than 15 but not raining print “It’s not raining but cold”. If it’s greater than or equal to 15 but not raining print “It’s warm but not raining”, and otherwise tell them “It’s warm and raining”.


#### QUESTION 16

	An allergy test produces a single numeric score which contains the information about all the allergies the person has (that they were tested for). The list of items (and their value) that were tested are:

  - eggs (1)
  - peanuts (2)
  - shellfish (4)
  - strawberries (8)
  - tomatoes (16)
  - chocolate (32)
  - pollen (64)
  - cats (128)
So if Tom is allergic to peanuts and chocolate, he gets a score of 34.

Write a program that, given a person’s score can tell them:
  a. whether or not they’re allergic to a given item
  b. the full list of allergies.


# END OF ASSSIGNMENT 

<!-- The **gentech** class is the *best*. The very best.

Things we cover in class:
* markdown
* loops
* lunch
+ hello
- world

1. first item
2. second item
3. third item

# pictures

![ScreenCap](./fortitude-valley-brunswick-street-new-farm-brisban.jpg)

# links

www.google.com

[Google](https://www.google.com)

# inserting code

``` ruby
if class == "smart"
  puts "Markdown is fun!"
  end
  ```

```
Hello World
if class == "smart"
  puts "Markdown is fun!"
  end
  ```
  
# quotes

> Special Quote <br>
Another Special Quote <br>
Everything is awesome # T1A1Workbook -->