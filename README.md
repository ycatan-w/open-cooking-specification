# Open Cooking Specification (OCS)

Open Cooking Specification (OCS) is a lightweight, structured format for representing recipes and culinary knowledge in a way that is both human-readable and machine-processable.

---

## What is OCS?

OCS defines a standard format for writing and sharing recipes in a structured way that is:

- human-readable
- machine-processable
- extensible
- implementation-independent

It is designed to support both simple recipes and complex culinary systems.

---

## Specification

The official specification is versioned.

Current version: 👉 **1.0.0**

You can read it here:

- [`versions/1.0.0.md`](./versions/1.0.0.md)

---

## Example

```yaml
openCooking: 1.0.0

info:
  title: Simple Recipe Collection

recipes:
  toast:
    name: Butter Toast

    ingredients:
      - name: Bread
        quantity: 2
        unit: slice

      - name: Butter
        quantity: 10
        unit: g

    steps:
      - instruction: Toast the bread.
      - instruction: Spread butter on top.
```

---

## Repository Structure

```
versions/
  1.0.0.md
README.md
LICENSE
```

---

## Status

OCS is actively designed for incremental evolution while preserving backward compatibility within minor versions.

---

## Contributing

Contributions are welcome (examples, tooling, extensions, improvements).

Please ensure changes remain backward compatible when possible.

---

## License

Apache License 2.0

See [LICENSE](./LICENSE)
