# Remove the Spacing in Excel

**Written By @0xAnsR**

### 1. Find All Spaces

Find the **Space** character using:

`<Space>`

> This means pressing the **Space key only**.

### 2. Replace All Spaces with `_`

Replace all spaces with:

`_`

**Underscore** (`_`)

Our target is:

* No starting-line spacing
* No double spacing
* No ending-line spacing

---

### 3. Remove Double Spacing

First, find double underscores:

`__`

Replace them with:

`!!`

Now replace:

`!!`

with:

`_`

This converts multiple spaces into a **single underscore**.

---

### 4. Save the Single Space Between Words

Use:

`?_?`

as the search key.

This means:

`[Alphabet]_[Alphabet]`

Replace it with any special character, such as:

```
`
```

or:

`|`

or any emoji.

This temporarily protects the single underscore between words.

---

### 5. Remove Starting-Line Spacing

Use:

`_?`

as the search key.

This means:

`_[Alphabet]`

Replace it with:

`<empty>`

> Leave the **Replace with** field empty.

Now the spacing at the **start of the line** is removed.

---

### 6. Remove Ending-Line Spacing

Use:

`?_`

as the search key.

This means:

`[Alphabet]_`

Replace it with:

`<empty>`

> Leave the **Replace with** field empty.

Now the spacing at the **end of the line** is removed.

---

### 7. Turn Back `[Alphabet]_[Alphabet]`

Now find the special character that was used in **Step 4**.

Replace it with:

`<Space>`

This restores the original **single space between words**.

---

## Finished

The result is:

* ❌ No spaces at the beginning of a line
* ❌ No double spaces
* ❌ No spaces at the end of a line
* ✅ Single spaces between words are preserved

**Written By @0xAnsR**
