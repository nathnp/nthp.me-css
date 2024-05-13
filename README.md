# NTHP.me CSS

This is the CSS file used for my website [nthp.me](https://nthp.me). 

This CSS file is a modified version of [simple.css](https://github.com/kevquirk/simple.css), and contains the following additions.

## Added Things

flexbox: To keep my posts tags from line braking

```CSS
.flexbox {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}
```

title: To easily give something the accent color

```CSS
.title {
  color: var(--accent)
}
```

invisTable: To make a table that is invisible, other than the content.

```CSS
.invisTable {
  td,
  th {
	border: 1px solid var(--bg);
	text-align: start;
	padding: 0.5rem;
  }
  
  th {
	background-color: var(--bg);
	font-weight: bold;
  }
  
  tr:nth-child(even) {
	/* Set every other cell slightly darker. Improves readability. */
	background-color: var(--bg);
  }
}
```

---

