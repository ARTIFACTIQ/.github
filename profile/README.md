# Artifactiq

### Intelligence in Every Frame

We build AI that **sees** what's valuable in visual content and **connects** it to real-world opportunities.

---

## What We Do

**Artifactiq** transforms passive images and video into interactive, monetizable experiences:

- **Detect** — AI identifies artifacts of interest in any visual content
- **Understand** — Scene graphs capture context and relationships
- **Connect** — Link artifacts to purchasable products
- **Experience** — Generate tourism packages from scenic locations

---

## Our Repositories

### SDKs & Tools
| Repo | Description |
|------|-------------|
| [`sdk-python`](https://github.com/ARTIFACTIQ/sdk-python) | Official Python SDK |
| [`sdk-javascript`](https://github.com/ARTIFACTIQ/sdk-javascript) | Official JS/TS SDK |
| [`cli`](https://github.com/ARTIFACTIQ/cli) | Command-line interface |
| [`examples`](https://github.com/ARTIFACTIQ/examples) | Integration examples |

### Documentation
| Repo | Description |
|------|-------------|
| [`docs`](https://github.com/ARTIFACTIQ/docs) | Documentation site |
| [`openapi`](https://github.com/ARTIFACTIQ/openapi) | API specifications |

---

## Quick Start

```python
from artifactiq import Artifactiq

client = Artifactiq(api_key="...")
result = client.analyze("image.jpg")

for artifact in result.artifacts:
    products = artifact.get_products()
    print(f"{artifact.label}: {len(products)} products found")
```

---

## Links

- [artifactiq.ai](https://artifactiq.ai)
- [docs.artifactiq.ai](https://docs.artifactiq.ai)

---

<p align="center">
  <sub>© 2026 Artifactiq · AI-Powered Visual Intelligence</sub>
</p>
