# YAML

### YAML is a digestible data serialization language often used to create configuration files with any programming language. Designed for human interaction, YAML is a strict superset of JSON, another data serialization language. But because it's a strict superset, it can do everything that JSON can and more.

---

## Features of Yaml

#### Here are some of the best features YAML has to offer.

## Commenting

YAML allows you to add comments to files using the **hash symbol** (#)

```
animals:
  name:#enter your name
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

## Data Types

Values in YAML's key-value pairs are scalar. They act like the scalar types in languages like Perl, Javascript, and Python. It's usually good enough to enclose strings in quotes, leave numbers unquoted, and let the parser figure it out. But that's only the tip of the iceberg. YAML is capable of a great deal more.

## Key-Value Pairs

> The key is always a string

> The value is a scalar so that it can be any datatype

## Number

**Javascript**

`let age=20`

**Yaml**

` age:20`

---

## String

**Javascript**

`let name="cat"`

**Yaml**

` name:cat` _or_ ` name:"cat"`

---

## Objects

**Javascript**

```
{
    animals:{
        name:"cat",
        age:20
    }
}
```

**Yaml**

```
animals:
  name:cat
  age:20
```

---

## Arrays

**Javascript**

```
  animals:[
    {
    name:"cat",
    age:20
    },
    {
    name:"dog",
    age:22
   }
  ]
```

**Yaml**

```
animals:
  - name: cat
    age: 20
  - name: dog
    age: 22
```
