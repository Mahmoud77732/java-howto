# Java + Spring Boot on VS Code 🚀

This guide explains how to set up and run Java and Spring Boot applications using Visual Studio Code (VS Code). It includes the required extensions, tools, and tips for a smooth development experience.

---

## 📦 Prerequisites

Make sure the following tools are installed on your system:

- [Java JDK 17+](https://adoptopenjdk.net/)
- [Maven](https://maven.apache.org/) or [Gradle](https://gradle.org/)
- [Visual Studio Code](https://code.visualstudio.com/)

---

## 🧩 Required VS Code Extensions

Install these extensions for full Java + Spring support:

### 🔹 Java Development
- ✅ **Java Extension Pack**  
  _Includes:_
  - Language Support for Java™ by Red Hat
  - Debugger for Java
  - Java Test Runner
  - Maven for Java
  - Java Dependency Viewer

### 🔹 Spring Boot Support
- ✅ **Spring Boot Extension Pack**  
  _Includes:_
  - Spring Boot Tools
  - Spring Initializr
  - Spring Boot Dashboard

### 🔹 Other Useful Extensions
- ✅ **Lombok Annotations Support** – If your project uses Lombok.
- ✅ **REST Client** – To test REST APIs from inside VS Code.
- ✅ **Docker** – For containerizing and managing Spring Boot apps.
- ✅ **GitLens** – Enhanced Git integration.
- ✅ **Path Intellisense** – Auto-suggestions for file paths and imports.

---

## 🛠️ How to Run a Spring Boot App

1. Clone or open your Spring Boot project in VS Code.
2. Make sure VS Code detects your project (it should auto-import if it's Maven or Gradle).
3. Open the `Application.java` class with `@SpringBootApplication`.
4. Click the **Run** or **Debug** link above the `main()` method.
5. Or, open the **Spring Boot Dashboard** and click the ▶️ icon to start the app.
6. You can also use the terminal:
   ```bash
   ./mvnw spring-boot:run     # For Maven
   ./gradlew bootRun          # For Gradle
   ```

---

## 🐞 Debugging Tips

- Use the **Run and Debug** tab to start a debug session.
- Set breakpoints in your code.
- Launch your app in **Debug mode** to inspect variables and call stacks.

---

## ⚠️ Common Problems & Fixes

| Problem | Solution |
|--------|----------|
| `Class not found` or red squiggles | Make sure Maven/Gradle project is properly imported |
| Lombok annotations not recognized | Install **Lombok Support** extension |
| No run/debug option on main method | Ensure the Java Extension Pack is fully installed |
| Port already in use error | Change `server.port` in `application.properties` |

---

## 📚 Related Resources

- [Spring Boot Documentation](https://docs.spring.io/spring-boot/docs/current/reference/html/)
- [VS Code Java Docs](https://code.visualstudio.com/docs/languages/java)
- [Spring Boot Tools for VS Code](https://marketplace.visualstudio.com/items?itemName=Pivotal.vscode-spring-boot)

---

## 📁 Repo Structure

```
java-howto/
├── java-vscode/
│   └── README.md   ← you're here
├── spring-errors/  ← (add more docs later)
└── tips-tricks/
```

---

Feel free to contribute with notes on issues you face and how you solved them! 💡
