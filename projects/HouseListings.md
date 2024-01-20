---
layout: project
type: project
image: img/HouseListingIcon.png
title: "House Listings"
date: 2022
published: true
labels:
  - Java
  - Data Structure
summary: "A project for ICS 211 that utilizes linked lists too record information for Houses that are for sale"
---

<img align="left" width="500" height="500" src="../img/HouseListingsimg.png" class="img-thumbnail">


This is a project that I made for my ICS 211 class that creates an application that runs in the terminal that would add houses and their information to a list. When you run the code it brings you to a menu where you can select an option by inputting the number that is next to the given option. You were given the options to add a house, remove a house, print all the houses, or the end the application. This project also dabbled into exception handling this would catch incorrect inputs and tell the user that they made a mistake. 

Since this was a solo project and probably one of the biggest projects we've done for the class, I learned various things about Java. One of the biggest things that I learned when I was coding this project was linking the many classes together. I remember having problems with calling to other classes because I had a hard time keeping up with the many classes implemented. I also deepened my learning about nodes and linked lists, and I got to learn and experience exception handling, which was fairly challenging but I eventually got the hang of it.

Here is a snippet of my code on how I handled the exception handling:
```java
 public class HouseException extends Exception {
   private String message;
   // Default Constructor  
   HouseException(){
      setMessage("");
   }
   // A set method for Exception Message
   public void setMessage(String message) {
      this.message = message;
   }
   // Get method that returns set Message
   public String getMessage() {
      return this.message;
   }
}

```

Source: <a href="https://github.com/Rickiace/House-Listings"><i class="large github icon "></i>Rickiace/House-Listings</a>
