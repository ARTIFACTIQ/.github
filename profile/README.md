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

### Core Engine
| Repo | Description |
|------|-------------|
| [`core`](https://github.com/ARTIFACTIQ/core) | High-performance Rust engine with ONNX & CoreML backends |
| [`releases`](https://github.com/ARTIFACTIQ/releases) | Pre-built binaries and website |

**Latest: v1.0.0-alpha.13** — CoreML support for Apple Silicon with 39 custom classes, 3.4x faster!

### SDKs & Tools
| Repo | Description |
|------|-------------|
| [`sdk-python`](https://github.com/ARTIFACTIQ/sdk-python) | Official Python SDK |
| [`sdk-javascript`](https://github.com/ARTIFACTIQ/sdk-javascript) | Official JS/TS SDK |
| [`examples`](https://github.com/ARTIFACTIQ/examples) | Integration examples |

### Documentation
| Repo | Description |
|------|-------------|
| [`docs`](https://github.com/ARTIFACTIQ/docs) | Documentation site |
| [`openapi`](https://github.com/ARTIFACTIQ/openapi) | API specifications |

---

## Quick Start

### CLI (Recommended)
```bash
# Install
curl -fsSL https://artifactiq.ai/install.sh | sh

# Analyze images (auto-downloads model on first use)
artifactiq analyze --input photo.jpg

# On Apple Silicon, use CoreML for 3.4x faster inference
artifactiq analyze --input photo.jpg --coreml
```

### Python SDK
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
