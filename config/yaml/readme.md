# YAML

### YAML is a digestible data serialization language often used to create configuration files with any programming language. Designed for human interaction, YAML is a strict superset of JSON, another data serialization language. But because it's a strict superset, it can do everything that JSON can and more.

---

## Features of Yaml

#### Here are some of the best features YAML has to offer.

## Commenting

YAML allows you to add comments to files using the **hash symbol** (#)

```
animals:
  name:# enter your name
  age:10

```

## Multi-document support

You can have multiple YAML documents in a single YAML file to make file organization or data parsing easier.

The separation between each document is marked by **three dashes** (---)

```
---
animals:
  name:cat
  age:10

---
animals:
  name:dog
  age:10
```
