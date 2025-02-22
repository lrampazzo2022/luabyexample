---
title: "String Functions"
weight: 14
# bookFlatSection: false
# bookToc: true
# bookHidden: false
# bookCollapseSection: false
# bookComments: false
# bookSearchExclude: false
---

# String Functions

Lua provides multiple string functions:

```
string
string.byte
string.char
string.dump
string.find
string.format
string.gmatch
string.gsub
string.len
string.lower
string.match
string.pack
string.packsize
string.rep
string.reverse
string.sub
string.unpack
string.upper
```

Split string:

```lua
local function splitStr(theString)

    local stringTable = {}
    local i = 1

    -- Cycle through the String and store anything
    -- except for spaces in the table
    for str in string.gmatch(theString, "[^%s]+") do
      stringTable[i] = str
      i = i + 1
    end

    -- Return multiple values
    return stringTable, i
end

local t = splitStr("I went for a walk.")
io.write(t[2], "\n", t[3])
```

```
went
for
```

{{< button relref="docs/gmatch"  >}}Next: Pattern Matching{{< /button >}}
