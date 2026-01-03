---
import BaseHead from '../components/BaseHead.astro';
import Footer from '../components/Footer.astro';
import Header from '../components/Header.astro';
import { SITE_DESCRIPTION, SITE_TITLE } from '../consts';
---

Hello!

Start Mermaid Info

```mermaid
  info
```

End Mermaid Info

Start Mermaid Diagram

```mermaid
flowchart TD

subgraph 2022
	A("a")
	F("f")
end

subgraph 2023
	B("b")
end

subgraph 2024
	C("c")
	D("d")
end

subgraph 2025
	E("e")
end

A --> B --> D --> E
A --> C --> D
A --> D
F-.->|unconfirmed| D

class A,B,C,D,E,F internal-link;
```

End Mermaid Diagram