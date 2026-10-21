```mermaid
flowchart LR
    U["User"] --> T["Terminal<br/>Emulator"]
    T --> PTY["Pseudo-Terminal"]
    PTY --> B["Bash<br/>Shell"]
    B --> P["Parse<br/>and<br/>Expand Command"]
    P --> R{"Command Type?"}

    R -->|Built-in| BI["Run inside<br/>Bash"]
    R -->|External| C["Create Child<br/>Process"]
    R -->|Script| S["Select Interpreter<br/>using shebang"]

    C --> E["Execute Program"]
    S --> E

    BI --> SC["System Calls"]
    E --> SC
    SC --> K["Operating System Kernel"]

    K --> F["File System"]
    K --> N["Network"]
    K --> M["Memory"]
    K --> D["Devices"]

    E --> O["stdout"]
    E --> ER["stderr"]
    O --> T
    ER --> T

    classDef main fill:#dcfce7,stroke:#16a34a,stroke-width:3px
    classDef kernel fill:#e0e7ff,stroke:#4f46e5
    class B main
    class K kernel
```

# Awesome Malicious [Shell](https://github.com/cybersecurity-dev/awesome-bash-scripting-resources) [Script](https://github.com/cybersecurity-dev/awesome-bash-scripting-language) Detection Scientific Research [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<p align="center">
    <a href="https://github.com/cybersecurity-dev/"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/github.svg" alt="GitHub"></a>
    &nbsp;
    <a href="https://www.youtube.com/@CyberThreatDefense"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/youtube.svg" alt="YouTube"></a>
    &nbsp;
    <a href="https://cyberthreatdefence.com/my_awesome_lists"><img height="20" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/blog.svg" alt="My Awesome Lists"></a>
    <img src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/bar.gif">
</p>

## 📖 Contents
- [2026](#2026) | [2025](#2025) | [2024](#2024) | [2023](#2023) | [2022](#2022) | [2021](#2021) | [2020](#2020) | [Others](#old)
- [My Other Awesome Lists](#my-other-awesome-lists)
- [Contributing](#contributing)
- [Contributors](#contributors)

### 2026
-
-
-

### 2025
-
-
-

### 2024
-
-
-

### 2023
-
-
-

### 2022
-
- 
-

### 2021
-
-
-

### 2020
-
-
-

### Old
-
-
-

##

### My Other Awesome Lists
You can access the my other awesome lists [here](https://cyberthreatdefence.com/my_awesome_lists)

### Contributing
[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors
[Thanks goes to these contributors](https://github.com/cybersecurity-dev/Awesome-Malicious-Shell-Script-Detection-Scientific-Research/graphs/contributors)!

### License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

[🔼 Back to top](#awesome-malicious-shell-script-detection-scientific-research-)
