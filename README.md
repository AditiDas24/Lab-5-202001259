# Lab-5-202001259
																																																																									[IT314]                                                                                                                                                      
<h3> Name : Aditi Das </h3>                                                                                                                                 
<h3> Student ID : 202001259 </h3>  
<h3> Date : 24th March 2023 </h3>  
  
 <br>

<h5> The link of the repository used is as follows : https://github.com/Andrea-Depe/Pac-man.git


<h3> Static Analysis </h3>
<h5> Static Analysis is the automated analysis of source code without actually executing the program. It helps us in detecting bugs, errors and finding out where code might be vulnerable. It checks for syntax, logic, data flow and security and other such issues. It can improve the reliablity and performance of the program. </h5>



#### Here, I am using flake8.

<h5> File Run : PacManGui.py </h5>

![image](https://user-images.githubusercontent.com/75675341/227481020-3dff66ab-781a-4d29-89c2-0ac0343718ea.png)

<h4> Types of errors that can be seen :</h4>

1. Module imported but not used (numpy) <br>
2. Line too long<br>
3. Indentation is not a multiple of 4 <br>
4. Other such formatting errors such as too many blank lines, too many whitespaces, <br>
   not leaving enough lines in between code, etc. <br>


<h5> File Run : PacMan_Hard.py </h5>

![image](https://user-images.githubusercontent.com/75675341/227483530-a78d179f-92fc-4735-afbf-62cca7c055f5.png)

<h4> Types of errors that can be seen :</h4>

1. Local variable assigned but never used (variable xtemp) <br>
2. Module imported but never used (time.time)
3. Indentation is not a multiple of 4 <br>
4. Other such formatting errors such as too many blank lines, too many whitespaces, <br>
not leaving enough lines in between code, etc. <br>


<h5> File Run : pacman_map.py </h5>

![image](https://user-images.githubusercontent.com/75675341/227488749-12296b86-de26-49b1-9934-7ca441400dee.png)

<h4> Types of errors that can be seen :</h4>

1. Multiple statements on one line <br>
2. Indentation is not a multiple of 4 <br>
3. Other such formatting errors such as too many blank lines, too many whitespaces, <br>
not leaving enough lines in between code, etc. <br>


<h5> File Run : Pacman_Test.py </h5>

![image](https://user-images.githubusercontent.com/75675341/227490154-056f62ab-1160-4550-bdd5-39a8e4310380.png)

<h4> Types of errors that can be seen :</h4>

1. Local variable assigned but never used (variable xtemp) <br>
2. Module imported but never used (Pacman.cookies)
3. Redeifinition of unused value. (big_cookies)<br>
4. Indentation is not a multiple of 4 <br>
5. Other such formatting errors such as too many blank lines, too many whitespaces, <br>
not leaving enough lines in between code, etc. <br>


<h5> Another thing to note here is that each error is preceeded by a character in red that represents a particular type of error. <br>
These error codes are as follows: </h5>

1. W - Warning : This represents specific programming language, in this case, Python related problems. These won't stop execution of code.
2. E - Error : These represent errors on a specific line of code that would hamper execution.
3. F : This is a part of pyflakes and represents the F class of error codes that represent unused variables, imports, etc.




 
