<br><p align="center">
[![Header](https://capsule-render.vercel.app/api?type=waving&color=0:1a0f2e,50:2d1b4e,100:1a0f2e&height=180&section=header&text=Pratham%20Khanduja&fontSize=55&fontColor=f0f0f5&animation=fadeIn&fontAlignY=50)](https://github.com/pratham-developer)
</p>
<p align="center">
  <a href="https://www.linkedin.com/in/pratham-khanduja"><img src="https://img.icons8.com/?size=100&id=xuvGCOXi8Wyg&format=png&color=000000" alt="linkedin" width="48" height="48" style="margin:8px;"/></a>
  <a href="https://www.instagram.com/say.pratham?igsh=MWFyM2J2N3lwOXRyZw=="><img src="https://img.icons8.com/?size=100&id=Xy10Jcu1L2Su&format=png&color=000000" alt="instagram" width="48" height="48" style="margin:8px;"/></a>
  <a href="mailto:prathk30@gmail.com"><img src="https://img.icons8.com/?size=100&id=EgRndDDLh8kS&format=png&color=000000" alt="mail" width="48" height="48" style="margin:8px;"/></a>
</p>
<br>
<h2> 🚀 &nbsp;About Me</h2>

```java
package com.github.pratham.controller;

import com.github.pratham.dto.Developer;
import com.github.pratham.service.AboutService;
import lombok.RequiredArgsConstructor;
import org.springframework.http.ResponseEntity;
import org.springframework.web.bind.annotation.*;

@RestController
@RequestMapping("/about")
@RequiredArgsConstructor
public class AboutController {

    private final AboutService aboutService;

    @GetMapping("/me")
    public ResponseEntity<Developer> getMe() {
        return ResponseEntity.ok(aboutService.getMe());
    }
}
```

```java
package com.github.pratham.service;

import com.github.pratham.dto.Developer;
import org.springframework.stereotype.Service;
import java.util.List;

@Service
public class AboutService {

    public Developer getMe() {
        return Developer.builder()
            .name("Pratham Khanduja")
            .location("Himachal Pradesh, India")
            .education("B.Tech CSE '27 @ VIT Vellore")
            .languages(List.of("Java", "Kotlin", "Python", "C", "C++", "JavaScript", "SQL"))
            .technologies(List.of("Spring Boot", "Node.js", "Express.js", "FastAPI",
                                  "Redis", "RabbitMQ", "PostgreSQL", "MySQL", "MongoDB"))
            .cloudAndTools(List.of("AWS", "Azure", "Docker", "GitHub Actions",
                                   "Vercel", "Firebase", "Supabase", "Git", "Linux", "Postman"))
            .currentlyLearning("production grade backend systems")
            .build();
    }
}
```
<br>
<h2> ⚡ &nbsp;Some Tools I Have Used and Learned</h2>
<br>
<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/androidstudio/androidstudio-original.svg" alt="android" width="48" height="48" style="margin:8px;"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original.svg" alt="java" width="48" height="48" style="margin:8px;"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/spring/spring-original.svg" alt="spring" width="48" height="48" style="margin:8px;"/>
  <img src="https://cdn.simpleicons.org/springboot" alt="spring boot" width="48" height="48" style="margin:8px;"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/kotlin/kotlin-original.svg" alt="kotlin" width="48" height="48" style="margin:8px;"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" alt="javascript" width="48" height="48" style="margin:8px;"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nodejs/nodejs-original.svg" alt="nodejs" width="48" height="48" style="margin:8px;"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mongodb/mongodb-original.svg" alt="mongodb" width="48" height="48" style="margin:8px;"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original.svg" alt="mysql" width="48" height="48" style="margin:8px;"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" alt="postgresql" width="48" height="48" style="margin:8px;"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/supabase/supabase-original.svg" alt="supabase" width="48" height="48" style="margin:8px;"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/firebase/firebase-original.svg" alt="firebase" width="48" height="48" style="margin:8px;"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/c/c-original.svg" alt="c" width="48" height="48" style="margin:8px;"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/cplusplus/cplusplus-original.svg" alt="cpp" width="48" height="48" style="margin:8px;"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" alt="python" width="48" height="48" style="margin:8px;"/>
</p>
