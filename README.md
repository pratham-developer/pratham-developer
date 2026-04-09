<br><p align="center">
[![Header](https://capsule-render.vercel.app/api?type=waving&color=0:1e3a8a,50:2563eb,100:1e3a8a&height=180&section=header&text=Pratham%20Khanduja&fontSize=55&fontColor=f8fafc&animation=fadeIn&fontAlignY=50)](https://github.com/pratham-developer)
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
import org.springframework.http.ResponseEntity;
import org.springframework.web.bind.annotation.*;
import java.util.List;

@RestController
@RequestMapping("/about")
public class AboutController {

    @GetMapping("/me")
    public ResponseEntity<Developer> getMe() {
        return ResponseEntity.ok(
            Developer.builder()
                .name("Pratham Khanduja")
                .location("Himachal Pradesh, India")
                .education("B.Tech CSE '27 @ VIT Vellore")
                .languages(List.of("Java", "Kotlin", "Python", "C", "C++", "JavaScript", "SQL"))
                .technologies(List.of("Spring Boot", "Node.js", "Express.js", "FastAPI",
                                      "Redis", "RabbitMQ", "PostgreSQL", "MySQL", "MongoDB"))
                .cloudAndTools(List.of("AWS", "Azure", "Docker", "GitHub Actions",
                                       "Vercel", "Firebase", "Supabase", "Git", "Linux", "Postman"))
                .currentlyLearning("production grade backend systems")
                .build()
        );
    }
}
```

<br>
<h2> ⚡ &nbsp;My Tech Stack</h2>

<h4 align="center">Languages</h4>
<p align="center">
  <img src="https://skillicons.dev/icons?i=java,kotlin,py,c,cpp,js" />
</p>

<h4 align="center">Frameworks & Technologies</h4>
<p align="center">
  <img src="https://skillicons.dev/icons?i=spring,nodejs,express,fastapi,redis,rabbitmq,postgres,mysql,mongodb" />
</p>

<h4 align="center">Cloud, DevOps & Tools</h4>
<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,azure,docker,githubactions,vercel,firebase,supabase,git,linux,postman" />
</p>
