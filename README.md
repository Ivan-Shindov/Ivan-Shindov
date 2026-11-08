 ### Hi there 👋
   /*  This is a short info about me. */
   
```java
@Component
public class HelloGit👋 {

   @NotNull
   private String name = "Ivan Shindov";
   
   @Min(1)
   private byte age = 28;
   
   private String address = "Sofia, Bulgaria";
   
   @NotNull
   private String currentJobTitle = "Java Backend Developer";
   
   @NotNull
   private String educationalInstitution = "Software University"
  
  
👨‍🎓 public String education() {
    return "Almost graduate with bachelor degree from National Sport Academy at Sofia - Kinesiotherapy. 
            Professional Certificate in Java Web Development from Software University";
   }
   
   
🖥 public String experience() {
    return "5+ years of experience building distributed microservices for sports betting
            and online casino platforms. Develops a multi-tenant
            casino aggregator integrating 20+ game providers";
   }
   
  
🛠 public String skills() {
    return "Self-disciplined, purposeful, communicative,
            oriented towards goals achieving and results, taking responsibility,
            problem solving and analytical thinking, root cause analysis, knowledge sharing";
   }
   
   
🌎 public List<String> interests() {
    return List.of("Java", "Spring", "PostgreSQL", "ScyllaDB", "Redis", "k8s");
   }

    
  ℹ️ public void moreInfo() {
     System.out.println("Got an interesting opportunity or just want to talk code ?
                         Say hi, I don't byte :smile:");
    }


   @Override
🏡 public String toString() {
    return "Thank you for your time!";
   }
}
```
