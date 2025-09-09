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

---

### 🌐 Portafolio

Explora mis proyectos, principios de arquitectura y enfoque profesional en mi portafolio en línea:  
🔗 [andresbc.vercel.app](https://andresbc.vercel.app)

O si prefieres algo más visual:  
[![Visita mi portafolio](https://img.shields.io/badge/Portafolio-AndresBC-blue?style=for-the-badge)](https://andresbc.vercel.app)

---

### 📫 Conectemos

- 💼 [LinkedIn](https://www.linkedin.com/in/andresbc-dev)
- 🧠 Apasionado por la arquitectura limpia, la escalabilidad y el liderazgo técnico.
- 🛠 Siempre buscando nuevas formas de mejorar la calidad del software y empoderar equipos.
