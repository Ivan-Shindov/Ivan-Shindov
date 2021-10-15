 ### Hi there 👋
   /*  This is a short info about me. */
   
```java
@Component
public class HelloGit👋  implements AboutMe {

   @NotNull
   private String name = "Ivan Shindov";
   
   @Min(1)
   private byte age = 23;
   
   private String address = "Sofia, Bulgaria";
   
   @NotNull
   private String currentJobTitle = "Reception administrator";
   
   @NotNull
   private String educationalInstitution = "Software University"
  
   @Override
👨‍🎓 public String education() {
    return "Almost graduate with bachelor degree from National Sport Academy at Sofia, with specialty - Kinesiotherapy.";
   }
   
   @Override
🖥 public String experience() {
    return "A little experience mainly communication with different types of people. Around two years experience with programming basically in Java";
   }
   
   @Override
🛠 public String skills() {
    return "Self-disciplined, purposeful, communicative, oriented towards goals achieving and results, taking responsibility "
            + "trying to learn everything in details, team player, not so very creative :smile:";
   }
   
   @Override
🌎 public List<String> interests() {
    return List.of("Java", "Spring", "MySQL", "a little JavaScript :smile:");
   }

    @Override
  ℹ️ public void moreInfo() {
     System.out.println("I like to gathering with friends in my free time and also write some code and learn new things :yum:");
    }


   @Override
🏡 public String toString() {
    return "Thank you!";
   }
}
```
