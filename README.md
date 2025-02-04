# YAML Training - Module 1: Introduction to YAML

## 1. Overview of YAML
YAML (Yet Another Markup Language or YAML Ain’t Markup Language) is a human-readable data format commonly used for configuration files and data serialization.

### Key Features:
- Simple and easy-to-read syntax
- Uses indentation (spaces, not tabs) to define structure
- Supports key-value pairs, lists, and dictionaries
- Extensively used in DevOps (Kubernetes, Docker, Ansible, CI/CD pipelines)

---

## 2. YAML vs JSON vs XML
| Feature  | YAML  | JSON  | XML  |
|----------|-------|-------|------|
| Readability | High | Moderate | Low |
| Syntax Complexity | Low | Moderate | High |
| Human-Friendly | Yes | Somewhat | No |
| Used For | Config files, automation | APIs, data exchange | Documents, web services |

Example Comparison:

### YAML:
```yaml
person:
  name: John Doe
  age: 30
  skills:
    - Kubernetes
    - Docker
    - YAML
```

### JSON:
```json
{
  "person": {
    "name": "John Doe",
    "age": 30,
    "skills": ["Kubernetes", "Docker", "YAML"]
  }
}
```

### XML:
```xml
<person>
  <name>John Doe</name>
  <age>30</age>
  <skills>
    <skill>Kubernetes</skill>
    <skill>Docker</skill>
    <skill>YAML</skill>
  </skills>
</person>
```

---

## 3. Basic YAML Syntax
### Key-Value Pairs
```yaml
name: John Doe
age: 30
city: New York
```

### Lists (Sequences)
```yaml
fruits:
  - Apple
  - Banana
  - Orange
```

### Dictionaries (Mappings)
```yaml
person:
  first_name: John
  last_name: Doe
  age: 30
  address:
    city: New York
    country: USA
```

### Nested Structures
```yaml
company:
  name: TechCorp
  employees:
    - name: Alice
      role: Developer
    - name: Bob
      role: DevOps Engineer
```

---

## 4. Data Types in YAML
### Strings
```yaml
message: "Hello, YAML!"
description: 'This is a string value'
```

### Numbers
```yaml
age: 30
pi: 3.14159
```

### Booleans
```yaml
is_active: true
is_deleted: false
```

### Null Values
```yaml
middle_name: null
```

---

## Conclusion
This module introduced YAML, its syntax, and basic data structures. The next module will cover more complex structures, including advanced YAML features.

**Next Module: YAML Data Structures**
