![Github Banner](https://github.com/AndresBC-Dev/images/blob/main/ANDRESBANNER.jpg)

```java
package profile;

import java.util.List;

public final class AndresBuitrago {
    private final String name = "Andres Buitrago";
    private final String role = "Software Architect & Team Lead";
    private final String location = "Barranquilla, Colombia";
    private final List<String> focus = List.of("Software Architecture", "Clean Code", "Distributed Systems", "Cloud");
    private final List<String> leadership = List.of("Mentorship", "Cross-disciplinary Projects", "Code Quality Advocacy");

    public void present() {
        System.out.printf("👋 %s — %s (%s)%n", name, role, location);
        System.out.println("🔍 Focus:");
        focus.forEach(f -> System.out.printf("  • %s%n", f));
        System.out.println("🤝 Leadership:");
        leadership.forEach(l -> System.out.printf("  • %s%n", l));
    }

    public String architecturePrinciples() {
        return "Design for observability, fail-fast, prefer simplicity over cleverness, automate quality checks.";
    }
}

```

