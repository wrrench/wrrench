``` java
import galaxy.earth.wrench;
public class Wrench{

    static void languages(){
        String languages = {"Java","TypeScript","C++","Python"};
        for(byte control = 0; control <= languages.length; control++){
            System.out.println("I code in :" + languages[control]);
        }
    }
    static void frameworks(){
        String frameworks = {"Next.JS","Spring Boot","Arduino","Express.JS","PyTorch","Keras","Log4J"};
        for(byte control = 0; control <= frameworks.length; control++){
            System.out.println("I write in " + frameworks[control] + " framework");
        }
    }
    static void about(){
        String goals = {"Open Source Community","Hound Wolf Squad, Inc."};
        for(byte control = 0; control <= goals.length; control++){
            System.out.println("Code to contribute to " + goals[control]);
        }
    }
    static void main(String args[]){
       Wrench cloak = new Wrench();
       cloak.languages();
       cloak.frameworks();
       cloak.about();
    }
}
```
<br><br><br>
![WRENCH](https://statx.vercel.app/api?username=wrrench)
![Top Langs](https://statx.vercel.app/api/top-langs/?username=wrrench&langs_count=8)
