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

` age: 20`

---

## String

YAML strings are Unicode. In most situations, you don't have to specify them in quotes.if you want you can

**Javascript**

`let name="cat"`

**Yaml**

` name: cat` _or_ ` name: "cat"`

---

## Boolean

YAML indicates boolean values with the keywords True, On and Yes for true. False is indicated with False, Off, or No.

**Javascript**

`let pet=true`

**Yaml**

```
pet: true
pet: On
```

## Objects

**Javascript**

```
let animals = {
  name: "cat",
  age: 20,
  pet: true,
};

```

**Yaml**

```
animals:
  name: cat
  age: 20
  pet: true

```

---

## Arrays

**Javascript**

```
  let animals = [
  {
    name: "cat",
    age: 20,
    pet: true,
  },
  {
    name: "dog",
    age: 22,
    pet: true,
  },
];

```

**Yaml**

```
animals:
  - name: cat
    age: 20
    pet: true
  - name: dog
    age: 22
    pet: true

```
