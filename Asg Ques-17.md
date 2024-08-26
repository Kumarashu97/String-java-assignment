Strings in Java  
Assignment Questions   
q1) What is a mutable string in java .Explain with an example ?  
Ans : If any changes is done inside the given string then it will reflect inside the same string   
Ex : StringBuilder str \= new StringBuilder(**"pwskills"**);  
str \= str.append(**"java"**);  
System.*out*.println(str);  
Q2 ) WAP to reverse a string   
Input :PWSKILLS  
Output : SLLIKSWP  
StringBuilder str \= new StringBuilder(**"PWSKILLS"**);  
str.reverse();  
   System.*out*.println(str);  
}  
q3) WAP to reverse the string while preserving the position ?  
Input : Think Twice  
Output : kniht eciwt  
Ans :  String str \= **"Think Twice"**;  
  String str1 \= **""**;  
  str \= str.toLowerCase();  
String arr\[\] \= str.split(**" "**);

for( String s : arr) {  
   for(int i=s.length()-1;i\>=0;i--) {  
       str1 \= str1 \+ s.charAt(i);  
   }  
  str1 \= str1 \+ **" "**;  
}  
      System.*out*.println(str1);  
q4) WAP to sort string alphabetically ?  
Ans : String str \= **"acdmlfhb"**;  
char ch\[\] \= str.toCharArray();  
Arrays.*sort*(ch);  
for(int i=0;i\< ch.length;i++) {  
   System.*out*.print(ch\[i\]);  
}

