![Github Banner](https://github.com/AndresBC-Dev/images/blob/main/ANDRESBANNER.jpg)

```java
Import andres.Desires2024;

public class WhoAmI {
    String name = "Andres Buitrago";
    String location = "Barranquilla-Colombia";
    String currentEdu = "Software Development Technician";
    String currentlyLearning = "Golang";
    String city;

     String[] hobbies = {"Movies", "Sports", "Series", "Travels"};

    public void getCity(String city) {
        String[] parts = location.split("-");
        city = parts[0].trim();

        System.out.println("I love this beautiful city called: " + city);
    }

    public void setAmbitions() {
        Desires2024 desires = new Desires2024();
        desires.BeHappy();
        desires.finishMyProjects();
    }
```

