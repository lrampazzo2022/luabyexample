---
title: "If/Else"
weight: 5
# bookFlatSection: false
# bookToc: true
# bookHidden: false
# bookCollapseSection: false
# bookComments: false
# bookSearchExclude: false
---

# If/Else

```lua
local age = 10
if age < 18 then
    print("under 18")
end

age = 20
if age > 18 then
    print("over 18")
elseif age == 18 then
    print("is 18")
else
    print("under 18")
end
```

Comparison operators in Lua:

```
==, <, >, <=, >=, ~= (inequality)
```

Combining Statements

```lua
local isAlive = false
local age = 19
if isAlive and age > 18 then
    print("good")
elseif not isAlive or age < 18 then
    print("either dead or under 18")
end
```

{{< button relref="docs/whilefor"  >}}Next: While/For{{< /button >}}
