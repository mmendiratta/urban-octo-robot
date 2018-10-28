# X-Team 47 TeleQueue

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

A telemarketing company has approached us to construct a system to match each potential sales point (consisting of demographic information, preferences, as well as a phone number) to a marketer who can effectively sell to them. this would be based on factors like language, gender, and other personal preferences. Each telemarketer has a wide variety of data points detailing whom they most effectively sell to. 

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)
TeleQueue


2. Output: Describe the output your program will produce.  Include and example format of the output produced.
* We will output a table with names of telemarketers, matched up with associated numbers of customers that they are most suitable to   interact with.
* Here is an example of the output, with an example of 4 telemarketers and 4 numbers. 
* | Telemarketer  | Customer Phone Number |
  | ------------- | ------------- |
  | John Johnson  | 608-456-7654  |
  | Dave Daveson  | 608-934-4656  |
  | Rob Robson  | 763-747-0987 |
  | Bill Billson  | 612-646-9386  |
* Here we see that each telemarketer can view the number that is most suitable for them to call 

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.



4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.
* Simple login menu screen for telemarketer to put their email and password into
* Should lead to display the numbers that telemarketer should be calling based on data from phone number
* Also allows them to edit number information after making a call

5. Types List: Break your solution idea down into units that you think can be implemented with a single class.
    ```
    Class SalesNode{
    
    }
    ```
    
    ```
    Class Marketer{
    
    }
    ```
    
    ```
    Interface TeleQueue{
    
    put(SalesNode N){
    //Adds and sorts a SalesNode into a marketer Queue 
    
    }
    
    get SalesNode (Marketer M){
    //Returns the highest priority node for a given marketer
    } 
    ```
    

Name each interface or class and briefly describe its function or purpose.


## Edit and Submit this file and any figures referenced by this document.

