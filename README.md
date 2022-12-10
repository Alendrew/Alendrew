## 💻 AboutMe.java 💻


package application;

import model.entities.Dev;

public class AboutMe {

	public static void main(String[] args) {
		
        System.out.println("👋 Hi, I’m André Alencar(@Alendrew)");
		
        System.out.println("👀 I’m interested in Java back-end development");

        System.out.println("📘 I study Technologist in System Analysis and Development at Fatec");
        
        System.out.println("📫 How to reach me -> https://www.linkedin.com/in/dev-alencar/");
        
        Dev andre = skills();
        
        System.out.println(andre.toString());
        
	}
        
	public static Dev skills(){
	
        String frontEnd = "HTML, CSS, JavaScript, Bootstrap";
	
        String backEnd = "Java, PHP, MySQL, UML, Springboot";
	
        return new Dev(frontEnd,backEnd);
        
	}   
	
}

## 👨‍💻 AboutMe in a nutshell 👨‍💻

👋 Hi, I’m André Alencar(@Alendrew)

👀 I’m interested in Java back-end development

📫 How to reach me -> https://www.linkedin.com/in/dev-alencar/

📘 I study Technologist in System Analysis and Development at Fatec

## 🛠 Skills

🙂 Front-end: HTML, CSS, JavaScript

🤯 Back-end: Java, MySQL, UML, Springboot 


<!---
Alendrew/Alendrew is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
