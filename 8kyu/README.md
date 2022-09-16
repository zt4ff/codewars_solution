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
