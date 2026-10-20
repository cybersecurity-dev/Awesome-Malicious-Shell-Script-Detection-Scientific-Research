```mermaid
flowchart LR
    U["User"] --> T["Terminal Emulator"]
    T --> PTY["Pseudo-Terminal"]
    PTY --> B["Bash Shell"]
    B --> P["Parse and Expand Command"]
    P --> R{"Command Type?"}

    R -->|Built-in| BI["Run inside Bash"]
    R -->|External| C["Create Child Process"]
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

# Awesome Malicious Shell Script Detection Scientific Research [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

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
[Thanks goes to these contributors](https://github.com/cybersecurity-dev/Awesome-Malicious-Powershell-Script-Detection-Scientific-Research/graphs/contributors)!

[🔼 Back to top](#awesome-malicious-shell-script-detection-scientific-research-)
