```java
public class Jannick {
    private int age = 18;
    private int height = 190;
    private String gender = "boy";
    private String color = "blue";
    private String occupation = "Electrician Apprentice";

    public String[] getProfile() {
        return new String[] {
            "age = " + age,
            "height = " + height,
            "gender = " + gender,
            "color = " + color,
            "occupation = " + occupation
        };
    }
}

public class AboutMe {
    public static void main(String[] args) {
        String[] aboutMe = new Jannick().getProfile();
        for(String information : aboutMe) {
            System.out.println(information);
        }
    }
}
```
