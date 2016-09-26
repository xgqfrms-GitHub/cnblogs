# Understand String Immutability 理解 Javascript 字符串的不变性

1

1

1

Understand String Immutability

 

In JavaScript, String values are immutable, which means that they cannot be altered once created.

For example, the following code:

var myStr = "Bob";
myStr[0] = "J";
cannot change the value of myStr to "Job", because the contents of myStr cannot be altered. Note that this doesnot mean that myStr cannot be changed, just that the individual characters of a string literal cannot be changed. The only way to change myStr would be to assign it with a new string, like this:

var myStr = "Bob";
myStr = "Job";
Instructions

Correct the assignment to myStr to achieve the desired effect.

 

1

1

1

1

1

1
![http://images2015.cnblogs.com/blog/928074/201609/928074-20160927020624953-636283667.png](http://images2015.cnblogs.com/blog/928074/201609/928074-20160927020624953-636283667.png)
![http://images2015.cnblogs.com/blog/928074/201609/928074-20160927020507781-1440233706.png](http://images2015.cnblogs.com/blog/928074/201609/928074-20160927020507781-1440233706.png)


https://www.freecodecamp.com/challenges/understand-string-immutability
支持(0)反对(0)
  修改删除 #2楼[楼主] 2016-09-27 02:05 anonymous007  
https://xgqfrms.github.io/HTML5/Web-Front-End-Job-Interviews/CSS3/3d-transition.html
http://www.cnblogs.com/xgqfrms/p/5782352.html
支持(0)反对(0)
  修改删除 #3楼[楼主] 2016-09-27 02:05 anonymous007  

支持(0)反对(0)
  修改删除 #4楼[楼主] 2016-09-27 02:06 anonymous007  
http://www.cnblogs.com/anonymous-ufo/p/5769280.html
支持(0)反对(0)
  修改删除 #5楼[楼主] 2016-09-27 02:06 anonymous007  


http://www.cnblogs.com/anonymous-ufo/p/5769280.html#3488975
