---
layout: post
title:  "Class Methods"
date:   2017-08-30 16:11:49 +0000
---


This was a really confusing concept for me. I didn't understand the use of class methods, or why I was asked to define a method, only to create a variable that I would then use within another method. It didn't make sense, and even upon completion of the lessons and getting code that worked, I really didn't understand what I was doing. I decided that I needed to take more time and delve in deeper to better understand these class methods, and what I was really accomplishing by using them. 

The example given in the Learn lesson was such:

class Dog
  def name=(dog_name)
    this_dogs_name = dog_name
  end
 
  def name
    this_dogs_name
  end
end

Prior to this, I had only been working with local variables. These are variables defined with a single enironment(methods in my limited experience), and only accessible from within that environment. These two methods seemed very redundant to me on first exposure to them. I had to read more about set and get methods to understands the first method #name= is the set method in this case. It set's a variable 'this_dogs_name' equal to the dog's name that it receives as input. The get method, #name, gets(shockingly!) this information that is stored within the set variable this_dogs_name.

This didn't seem that impressive at first. At some point it hit me though: I couldn't have done this previously. With the methods I'd been using previously, I was never able to access a variable from one method within another method. Although still basic, this is a cool new application to me, by use of class methods. 

Namaste - J
