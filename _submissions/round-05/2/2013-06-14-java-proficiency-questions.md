---
date: 2013-06-14
round: Round 5
title: Java Proficiency Questions
author: Jordan Fish
permalink: /2013/06/java-proficiency-questions/
tags:
  - Proficiency
---
Novice/Intermediate

1. Which of the following is not a Java keyword?

a. public  
b. static  
c. class  
d. interface  
e. const

&nbsp;

Intermediate/Expert

2. Consider the following Java snippet

StringBuffer sb = new StringBuffer("123&#8243;);  
doSomething(sb);  
doSomethingElse(sb);

private void doSomething(StringBuffer s)  
{  
s.append("4&#8243;);  
}

private void doSomethingElse(StringBuffer s)  
{  
s = new StringBuffer("abc");  
}

what will be contained in sb before doSomething, after doSomething, and after doSomethingElse

a. 123, 123, 123  
b. 123, 1234, abc  
c. 123, 123, abc  
d. 123, 1234, 1234
