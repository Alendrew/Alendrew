## π» AboutMe.java π»


package application;

import model.entities.Dev;

public class AboutMe {

	public static void main(String[] args) {
		
        System.out.println("π Hi, Iβm AndrΓ© Alencar(@Alendrew)");
		
        System.out.println("π Iβm interested in Mobile application development");

        System.out.println("π I study Technologist in System Analysis and Development at Fatec");
        
        System.out.println("π« How to reach me -> https://www.linkedin.com/in/dev-alencar/");
        
        Dev andre = skills();
        
        System.out.println(andre.toString());
        
	}
        
	public static Dev skills(){
		
        String frontEnd = "HTML, CSS, JavaScript";
        
        String backEnd = "Java, Data Structures in C, MySQL, UML";
        
        return new Dev(frontEnd,backEnd);
        
	}   
	
}

## π¨βπ» AboutMe in a nutshell π¨βπ»

π Hi, Iβm AndrΓ© Alencar(@Alendrew)

π Iβm interested in Mobile application development

π« How to reach me -> https://www.linkedin.com/in/dev-alencar/

π I study Technologist in System Analysis and Development at Fatec

## π  Skills

π Front-end: HTML, CSS, JavaScript

π€― Back-end: Java, Data Structures in C, MySQL, UML

<!---
Alendrew/Alendrew is a β¨ special β¨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
