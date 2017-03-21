# Lets Put Week 2 All Together

## The Web
![Image of Web](https://media.serious.io/a5bea1fcf2a98412/serious.gif)
When we speak about the Web we must cover the internet. The internet is a backbone
of a millions of networks to be connected to each other. It has services that use it
to be able to reach millions of people. The Web is one if not the largest of these services.
So how does the Web work or better yet how do we interact with the Web. We have done many
times without thinking about. The first thing we do is open a **_[browser](#wb)_** and enter an
address (URL). For this to work we have **_[Domain Name](#dns)_**. The sit must also be **_[hosted](#web-hosting)_**
somewhere to allows us to access it. After we enter the address a message is sent using **_[HTTP](#ht)_**
to the server were this sit is stored. After all the background processes are finished in our
**_[browser](#wb)_** we see the site. Sometime it is amazing that all this works. There are so many things that have to go right for this to happen every time to ask to see a sit.

## Algorithms
![Algorithms](https://www.tutorialspoint.com/data_structures_algorithms/images/tower_of_hanoi.gif)

At its core algorithms are used to figure out how to do things in a step by step mode. It can be shown either by listing each step or using a flowchart. This helps with brain storming and seeing if any steps are being missed or how things are tied to each other.
There are many methods that can bring this to life in programing. These list will help to see what type of Data Structures you would use. You could also see if you could use **_[Recursion](#re)_**, **_[Sorting](#so)_** or **_[Functional Programming](#fp)_** to make this come to fruition.   
These steps are easy for computer to understand. They do well in following steps in order and can doing it very quickly. Algorithms also make it easy to see how well it can scale itself compared to its input. This is where Big O Analysis comes into play. **_[Big O Analysis](#bo)_** puts how well it can scale into a mathematical expression so you could better understand if the steps are being done as efficient as possible.  




***  

### Explanation of stand alone topics  

#### <a id="web-hosting"></a> Web Hosting
Web Hosting is a service that allows you to be able to have you website put on the Web.
This is possible because companies have servers were you are able to load your files that
are needed for you website. You are basically renting the space out on the servers allowing
other computer to be able to access your website through their servers.

#### <a id="dns"></a> Domain Name System
A domain name is just the name of your website. It is the identity of your website.
You have to have a domain name to be able to have a website.
The domain name must also be registered for this to work. Think of a website as a
house, your house has an address so others can find it. The same for you domain
name, it need to be registered so others can find your website.
When you register you domain name you will also have a suffixes (.com or .gov),
many of these domains have requirements. For example if you are registering a
government website or an educational one will make a difference.
You must make sure all your information for your website in accurate when you
are registering it. If you make a mistake on this information if will cause you
website to have errors and page-load failures. This will not allow people to view your website.

#### <3 id="wb"></a> Web Browser
We all have used a browser. Some have used chrome or maybe Explore form Microsoft.
But have you stop to think how it works.
When you enter an address in the browser it send a request to the server were the
website is stored. After a couple of background communications happen a website
is returned in HTML form. The browser then translates this and displays the website
into a form that make sense to the user.

#### <h id="ht"></a> HTTP
HTTP is a type off communication that is used by the browser to be able to send request through the internet to request access to a website. This happens by the browser sending a request to the webserver using an HTTP. Then the server sends back an HTTP response which contains all the information that the browser will need to be able to display the website.
The HTTP request is made up three parts. First would be the request line then you would have a request header and last the request body.  The HTTP response is made up of the same three parts expect they are called response instead of request.


#### <d id="bo"></a> Big O Analysis
Big 0 Analysis is a mathematical expression used to figure out how well a program scales compared to its input. It takes into account best and worst case scenarios. The best case would be O(1) and this would be possibly in programs that are outputting a variable. It does not matter how long or short it is because it is only on step and nothing is being done to the variable just outputting. Next you have O(n) which is considered Fair. You then have O(n log n) falling into the Bad. The last ones are O(n^2), O(2^n) and O(n!) which all fall into horrible.
The object is to write the best code possible. You will not always be in the Fair or Good range. But this would be the goal. There are many factors that would come into play. Sometimes for it to function and do the things you want it to do. It will not be in the fair band.
The only thing you can do it wright the best code that you can.

#### <e id="fp"></a> Functional Programing
The main key ideal of Functional Programing is the execution of mathematical functions.
In its self it is made of tool sets that are used to solve problems. It is deeply rooted in mathematical thinking. It is not language dependent. What makes it very different from other types of tools is that inputs once set cannot be changed. So this means it cannot use loops or counters. You would think this would make it impossible to write code to solve problems. But this is the simplicity of this tool.  In any language you will have trade off pros and cons. There is no difference with Functional Programing.

#### <f id="re"></a> Recursion
Recursion is a function that calls itself. Since it calls itself you must first make sure that you can get out of the loop once you solve the problem or if you didn’t have to use it in the first place. If not you would end up in an endless loop. It allows you to write less code and be able to run it more efficient. For this to work you would need a stack. Since you are looping that gives you and output for each loop. This will continue till you get the result you are looking for. Since you are using the answer to feed the next loop. This is the reason you are in need of a stack.

#### <g id="so"></a> Sorting
Sorting is the same meaning in programing as in the world around us. You are put things in order either by high to low or even by which page that has the most visitors. You can sort using any properties that you choose from. You would have to start with a list to be able to sort.  Why is sorting so important. It can be broken down using an example.
If a list is stored as unsorted and you try to do a search. You would have to do a laniary search. This means you would have to start with the first element of the list and keep moving through it till you find the one you were looking for. In a worst case scenario, it could end up being the last one. This would not be very efficient and take a long time to run.  
This is the reason that the most important thing to know about sorting is that you must start out with list.
