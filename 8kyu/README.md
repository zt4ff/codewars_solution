<details>
<summary>1. Abbreviate a Two Word Name</summary>

Write a function to convert a name into initials. This kata strictly takes two words with one space in between them.

```js
// javascript
function abbrevName(name) {
  const splittedName = name.toUpperCase().split(" ");
  return `${splittedName[0][0]}.${splittedName[1][0]}`;
}
```

```python
# python
def abbrev_name(name):
    splittedName = name.upper().split(" ")
    return f'{splittedName[0][0]}.{splittedName[1][0].upper()}'

```

```java
// java
public class AbbreviateTwoWords {

  public static String abbrevName(String name) {
    String[] splittedName = name.toUpperCase().split(" ");
    return String.format("%s.%s", splittedName[0].charAt(0), splittedName[1].charAt(0));
  }
}
```

</details>
<details>
<summary>2. Reversed Strings</summary>

Complete the solution so that it reverses the string passed into it.

```python
def solution(s):
    res = ""
    for c in s:
        res = c + res
    return res
}
```

```js
// javascript
function solution(str) {
  return str.split("").reverse().join("");
}
```

</details>

<details>
<summary>3. Remove duplicates from list</summary>

Complete the solution so that it reverses the string passed into it.

```js
// javascript
function distinct(a) {
  return Array.from(new Set(a));
}
```

</details>
