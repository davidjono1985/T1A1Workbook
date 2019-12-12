# T1A1 - WORKBOOK
#### By David Johnson

# QUESTION 1
Five key events:

#### 1. Creation of the Domain Name System (DNS)

DNS was invented by Paul Mockapetris, with the original specifications published by the Internet Engineering Task Force in November 1983.  

DNS is considered to be the backbone of the internet as we know it - a decentralized and hierarchical naming system that connects URLs with their IP addresses,  making it possible to type words into a browser instead of a string of numbers.  

There were seven “top-level” domain names created - gov, edu, com, net, org, mil and int.


#### 2 Protocol Wars
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

#### Commercialization of the internet

 Although there were already commercial enterprises in existence, it wasn’t until 1995 that the internet was first considered to be truly commercialized.  This was due, in part to the development of SSL encryption (Secure Sockets Layer) which allowed for safe financial transactions. It was also the year two major companies were started – the Echo Bay (now EBAY) and Amazon.com

 The introduction of https (the hypertext transfer protocol encrypted with SSL) as well as user-friendly web browsers and major internet service providers contributed to the dot com boom of the late 1990's.

#### QUESTION 2

#### PACKETS
Packets allow large pieces of information to be transferred accross the TCP/IP network by breaking the data down into smaller pieces or "packets" in order to be compiled again at the other end .  This technology was of critical importance in the development of the internet as it allows for different bandwidths and potential interference while tranferring data from one IP address to another.


#### IP ADDRESSES (IPv4 and IPv6)

IP (internet protocol) addresses are the “digital addresses” used by computers/digital devices - each device has a unique IP address.  This is important because you first need to be able to locate and differentiate between devices before being able to send and receive information.

The common type of IP address is known as IPv4, for "version 4" which uses a  32-bit address space and supports a maximum of 4.3 billion unique IP addresses.

The IPv6 address was later created which consists of eight groups of four hexadecimal digits so theoretically this will never run out of unique addresses.

#### ROUTERS AND ROUTING

A router is a device that relays data packets between computer networks. The process of routing involves assessing a packet received from one host and directing it to the next network.  In order to determine which interface the packet should be forwarded to, routers use routing policies or routing tables (a list of known routes). 

#### DOMAINS AND DNS

A domain is a collection of internet addresses that share a common suffix, or under the control of a particular organization or individual. DNS (Domain Name System) is the global database that connects IP addresses with their corresponding domain names. This has greatly helped the internet's usability as it allows users to enter familiar words instead of complex numbers.

#### QUESTION 3

Define the features of the following technologies that are essential in terms of the development of the internet:
  - TCP
  - HTTP and HTTPS
  - web browsers (requests, rendering and developer tools)

Explain how each technology has contributed to the development of client and server communication over the internet

    50 - 150 words for each technology

#### QUESTION 4

Identify THREE data structures used in the Ruby programming language and explain the reasons for using each.	

    50 - 100 words on each data structure

#### QUESTION 5

Describe the features of interpreters and compilers and how they are different.	

    100 - 200 words on each way code is executed.

#### QUESTION 6

Identify TWO commonly used programming languages and explain the benefits and drawbacks of each.	

    200 - 400 words on each language

#### QUESTION 7

Identify TWO ethical issues from the areas below and discuss the extent to which an IT professional is ethically responsible in terms of the issue.

List of topics containing ethical issues:
  - access to a user’s personal information (medical, family, financial, personal attributes such as sexuality, religion, or beliefs)
  - intellectual property, copyright, and acknowledgement.
  - criminal acts such as theft, fraud, trafficking and distribution of prohibited substances, terrorism
  - GPS tracking data and other types of metadata, MAC addresses, hardware fingerprints
  - freedom of thought, conscience, speech and the media
  - aggressive sales and marketing practices designed to mislead and deceive consumers
  - trading of shares on the stock exchange OR crypto-currencies

For each ethical issue identify a source of legal information relating to the ethical issue and discuss whether the law is helpful in assisting a developer to act in an ethical way.

Conduct research into a case study of ONE of the ethical issues you have chosen discuss how an ethical IT professional should respond to the case study and how they might mitigate or prevent ethical breaches.	

    200 - 400 words for each ethical issue

#### QUESTION 8

Explain control flow, using an example from the Ruby programming language	

    100

#### QUESTION 9

Explain type coercion	100

#### QUESTION 10

Describe the data types recognised by the Ruby programming language. In your description you should give example code which uses each data type, and include the name of the Ruby classes which represent each data type.	

    100

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

The **gentech** class is the *best*. The very best.

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
Everything is awesome # T1A1Workbook