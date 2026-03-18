# clipspyx Colab Notebooks

Interactive notebooks for [clipspyx](https://github.com/inferal-oss/clipspyx), the Python DSL for [CLIPS](https://clipsrules.net).

## Notebooks

| Notebook | Description | Open |
|----------|-------------|------|
| [k8s-rules.ipynb](k8s-rules.ipynb) | Kubernetes cluster management with declarative rules | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/inferal-oss/clipspyx-colab/blob/main/k8s-rules.ipynb) |

## What is clipspyx?

clipspyx lets you write CLIPS rule engine logic as annotated Python classes. Instead of nested if/else chains, you declare independent rules that react to facts. The engine handles pattern matching, execution order, and truth maintenance.

```bash
pip install clipspyx[dsl,64x]
```

See the [clipspyx repository](https://github.com/inferal-oss/clipspyx) for full documentation.
