# unicode template

```javascript
[][(({})+[])[-~-~-~-~-~[]]+(({})+[])[-~[]]+($+[])[-~-~[]]+(![]+[])[-~-~-~[]]+(!![]+[])[+[]]+(!![]+[])[-~[]]+([][[]]+[])[+[]]+(({})+[])[-~-~-~-~-~[]]+(!![]+[])[+[]]+(({})+[])[-~[]]+(!![]+[])[-~[]]]
[(({})+[])[-~-~-~-~-~[]]+(({})+[])[-~[]]+($+[])[-~-~[]]+(![]+[])[-~-~-~[]]+(!![]+[])[+[]]+(!![]+[])[-~[]]+([][[]]+[])[+[]]+(({})+[])[-~-~-~-~-~[]]+(!![]+[])[+[]]+(({})+[])[-~[]]+(!![]+[])[-~[]]]
((!![]+[])[-~[]]+(!![]+[])[-~-~-~[]]+(!![]+[])[+[]]+([][[]]+[])[+[]]+(!![]+[])[-~[]]+([][[]]+[])[-~[]]+(/ /+[])[-~[]]+
(/"/+[])[-~[]]+(/\\/+[])[-~[]]+([][[]]+[])[+[]]+

/* 0 */ -[]+
/* 0 */ -[]+
/* 6 */ -~-~-~-~-~-~[]+
/* 8 */ -~-~-~-~-~-~-~-~[]+

(/"/+[])[-~[]])()
```

# unicode converter

```javascript
const unicode = code => {
	const dict = {
		0: "+[]+[]",
		1: "-~[]+[]",
		2: "-~-~[]+[]",
		3: "-~-~-~[]+[]",
		4: "-~-~-~-~[]+[]",
		5: "-~-~-~-~-~[]+[]",
		6: "-~-~-~-~-~-~[]+[]",
		7: "-~-~-~-~-~-~-~[]+[]",
		8: "-~-~[]<<-~-~[]+[]",	
		9: "-~-~-~[]*-~-~-~[]+[]",
		a: "(![]+[])[-~[]]",
		b: "({}+[])[-~-~[]]",
		c: "($+[])[-~-~-~[]]",
		d: "([][[]]+[])[-~-~[]]",
		e: "([][[]]+[])[-~-~-~[]]",
		f: "(![]+[])[+[]]"
};	

	return `[][(({})+[])[-~-~-~-~-~[]]+(({})+[])[-~[]]+($+[])[-~-~[]]+(![]+[])[-~-~-~[]]+(!![]+[])[+[]]+(!![]+[])[-~[]]+([][[]]+[])[+[]]+(({})+[])[-~-~-~-~-~[]]+(!![]+[])[+[]]+(({})+[])[-~[]]+(!![]+[])[-~[]]][(({})+[])[-~-~-~-~-~[]]+(({})+[])[-~[]]+($+[])[-~-~[]]+(![]+[])[-~-~-~[]]+(!![]+[])[+[]]+(!![]+[])[-~[]]+([][[]]+[])[+[]]+(({})+[])[-~-~-~-~-~[]]+(!![]+[])[+[]]+(({})+[])[-~[]]+(!![]+[])[-~[]]]((!![]+[])[-~[]]+(!![]+[])[-~-~-~[]]+(!![]+[])[+[]]+([][[]]+[])[+[]]+(!![]+[])[-~[]]+([][[]]+[])[-~[]]+(/ /+[])[-~[]]+(/"/+[])[-~[]]+(/\\//+[])[-~[]]+([][[]]+[])[+[]]+-[]+-[]+(${dict[code[0]]})+(${dict[code[1]]})+(/"/+[])[-~[]])()`;
};
```
