# Reference-Variable

class Student{     
         int id;    
         String name;   
}  
class TestStudent3{  
public static void main(String args[]){  
        //Creating objects  
        Student s1=new Student();  
        Student s2=new Student();  
//Initializing objects  
          s1.id=51;  
           s1.name="Jisoo";  
         s2.id=52;  
           s2.name="Jennie";  
           //Printing data  
                  System.out.println(s1.id+" "+s1.name);  
                  System.out.println(s2.id+" "+s2.name);  
         }  
}  


OUTPUT:
51 Jisoo
52 Jennie
