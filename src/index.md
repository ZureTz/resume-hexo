---
# Language (Optional)
lang: en
# Site Keywords & Description
keywords: Resume, Software Engineer, Computer Science
description: Professional resume of Jinsong Huang
# Resume Title
resume_title: Jinsong Huang's Resume
# Job Applicant Name
name: Jinsong Huang
avatar: https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/avatar/avatar.png
# Contact
contact:
  - icon: fas fa-globe-asia
    text: https://resume.trozure.uk
    url: https://resume.trozure.uk
  # Email
  - icon: fas fa-envelope
    text: pineehuang@icloud.com
    url: mailto:pineehuang@icloud.com
  # Phone Number
  - icon: fas fa-phone-alt
    text: +86 18163384338
    url: tel:+86-18163384338
# PDF Download Link
download:
  title: Download Source Code
  icon: fas fa-download fa-fw
  url: https://github.com/ZureTz/resume-hexo
---

{% raw %}
<center>
<a href='/'>English</a> | <a href='/zh-cn/'>简体中文</a>
</center>
{% endraw %}

## <i class="fas fa-clipboard-check"></i> Professional Summary

- **Technical Proficiency**: Proficient in C/C++, Python, JavaScript and other mainstream programming languages, familiar with Go/Java, capable of solving complex technical problems with solid foundation in data structures, algorithms, operating systems, and networking principles
- **System Development**: Experienced in Linux development environment, proficient with Git and other version control tools
- **Learning Efficiency**: Strong self-learning ability, quick adaptation to new technology stacks and development environments, continuous learning mindset, fluent in reading English technical documentation with independent problem-solving capabilities
- **Team Collaboration**: Clear communication and expression, strong teamwork awareness, excellent project coordination skills and responsibility, experienced in open source contributions with recognized Issues and PRs by maintainers

## <i class="fas fa-user-graduate"></i> Education

**China University of Petroleum (Beijing) (211)** 
- **B.S. in Computer Science and Technology, School of Artificial Intelligence**
- **Expected Graduation: June 2026**
- **GPA: 4.0/5.0 (Top 5%)**
- **IELTS: 7.5**

## <i class="fas fa-user-tie"></i> Experience

#### Teaching Assistant @ China University of Petroleum (Beijing)
**March 2025 - June 2025**

- Partially responsible for maintaining and optimizing the department's Online Judge system (acm.cup.edu.cn)
- Assisted professors in organizing and migrating 100+ programming problem sets, designed scoring criteria and automated test cases, improving evaluation accuracy
- Provided one-on-one tutoring to 20+ undergraduate students, resolved technical challenges, conducted code reviews, enhancing students' programming capabilities
- Led programming practical sessions for 50+ students, training them in standard development workflows and toolchains, achieving high teaching satisfaction ratings

## <i class="fas fa-award"></i> Projects

### os-webserver - High-Performance Web Server
**May 2024 - June 2024** Architecture Design and Implementation

Self-designed and implemented high-performance HTTP server, building complete web server architecture from scratch.

Tech Stack: `C` `Make` `Pthread` `GLib` `FUSE`
- Addressed high-concurrency access demands through Linux Pthread thread pool technology, achieving 1000%+ performance improvement
- Reduced repeated request processing overhead by implementing HTTP request caching mechanism using glib data structures (binary search tree and hash table)
- Enhanced file access efficiency by integrating fuse and other core libraries to build lightweight in-memory file system, achieving 100% speed improvement
- Key Learnings: Gained deep understanding of HTTP protocol and web server architecture design principles, mastered Linux system programming and multi-threaded concurrency control, familiar with file system low-level interfaces and memory mapping mechanisms
- Project Outcome: Achieved performance metrics unattainable by traditional single-threaded servers through system-level optimization, received highest evaluation for code quality and technical innovation in university operating systems course
- GitHub: [https://github.com/ZureTz/os-web-server](https://github.com/ZureTz/os-web-server)

### shorter-url - URL Shortening Service
**March 2025 - April 2025** Core Feature Design and Implementation

Designed and implemented a URL shortening service to solve the inconvenience of sharing long URLs and link management difficulties. The system provides core features including short link generation, custom aliases, and expiration management, improving sharing efficiency through a centralized link management platform.

Tech Stack: `Go` `Echo` `JWT` `PostgreSQL` `Redis`

- Adopted frontend-backend separation architecture to meet modern web application UX requirements, built high-performance RESTful API with Go/Echo and responsive interface with Next.js/React
- Addressed performance bottlenecks in high-volume link access by storing core data in PostgreSQL and caching popular links in Redis, significantly improving user access experience
- Ensured user data security through JWT authentication mechanism and Bcrypt password encryption, with email verification code recovery functionality
- Implemented custom alias, expiration settings, and personal management panel features to meet user personalization needs
- Reduced operational costs through scheduled tasks for automatic expired data cleanup, database migration tools for schema management, and Docker containerization for simplified deployment
- Repository: [https://github.com/ZureTz/shorter-url](https://github.com/ZureTz/shorter-url)
- Live Demo: [https://s.trozure.uk](https://s.trozure.uk)

## <i class="fas fa-code"></i> Open Source Contributions

- **[KhronosGroup/Vulkan-Samples](https://github.com/KhronosGroup/Vulkan-Samples)**: Discovered and fixed technical errors in API documentation, submitted comprehensive documentation improvements, recognized and merged by project maintainers
- **[MaiM-with-u/MaiBot](https://github.com/MaiM-with-u/MaiBot)**: Fixed WebUI dynamic configuration functionality module, resolved configuration challenges, received positive feedback from project maintainers

## <i class="fas fa-laptop-code"></i> Technical Skills

- **Programming Languages**: C/C++, Go, TypeScript, Python
- **Technical Frameworks**: Linux system programming, Gin/Echo, SQLc, PostgreSQL, Redis, RESTful API debugging (Postman), Web backend development (Go), Web frontend development (React, TypeScript)
- **Development Tools**: Linux, Git, VS Code, Docker
- **Soft Skills**: Excellent teamwork and communication abilities; Strong English proficiency (IELTS 7.5) with independent English technical documentation reading capability

## <i class="fas fa-phone-alt"></i> Contact Me

Currently: Student, available for internships lasting 3+ months, can start within one week.

<i class="fas fa-envelope fa-fw"></i> [pineehuang@icloud.com](mailto:pineehuang@icloud.com)
<i class="fas fa-phone-alt fa-fw"></i> [+86 18163384338](tel:+86-18163384338)

## Comments

{% raw %}
<script src="https://utteranc.es/client.js"
        repo="ZureTz/resume-hexo"
        issue-number="18"
        theme="github-light"
        crossorigin="anonymous"
        async>
</script>
{% endraw %}
