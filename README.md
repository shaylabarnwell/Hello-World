# Hello-World
For my Java programming class

public class AboutMe {

  public static void main(String[] args) {
    printHeader();
    printIntroduction();
    printSkills();
    printInterests();
  }

  private static void printHeader() {
    System.out.println("# About Me\n");
  }

  private static void printIntroduction() {
    String introduction = "Hello, I am Shayla. I am aspiring Application Developer currently studying at Central Piedmont community college. I strive to solve daily life struggles through code. I believe if you dive into the power that technology has it can have an everlasting impact.";
    
    System.out.println(introduction);
  }

  private static void printSkills() {
    String skills = "## Skills\n"
                       "Basic knowledge in Python, Java, C++, Swift \n" +
                       "limited knowledge in HTML and CSS" +
                       "Leadership, adaptability, creative, and openmindedness\n";

    System.out.println(skills);
  }

  private static void printInterests() {
    String interests = "## Interests\n" +
                       "Cloud\n" +
                       "Software Development\n" +
                       "Machine Learning\n" +
                       "New Technologies\n";
  
     System.out.println(interests);                  
  }
}  
