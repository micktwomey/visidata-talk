# I ❤️ VisiData
## PyLadies Dublin Feb 2023
### Michael Twomey


This talk is about VisiData

I'm going to be demoing it so expect some fun as I switch back and forth

---

# Who am I?

---

# Michael Twomey

	Senior Cloud Architect at fourTheorem
	I help clients with AWS and Python development

Yes I don't know what a senior cloud architect is either

	I've been working with messy data for 20+ years
	Messy data isn't just for Data Scientists 😆

	I'm an unashamed UNIX user
	I live in the terminal (most of the time)

---

	I like Terminal based applications

	I frequently have to deal with random data

---

# What is VisiData?

---

	https://visidata.org/

/assets/Clipboard.png
size: contain

Think Excel for your command line with python scripting

Or think what would happen if Excel had vim or emacs style key bindings?

---

# Is VisiData for You?

```sh
pip install visidata
vd myfile.csv  
```

```
pipx run visidata myfile.csv
```

	If you love Excel and are proficient in it, probably not

	If you hate the terminal definitely not!

	If you hate learning keybindings this isn't for you!

If you frequently finding yourself wanting to quickly look at some data it might be

If you like using the terminal probably!

---

# Demo Time!

---

# Titanic Dataset

---

# The Complete Titanic Dataset

	https://bit.ly/kaggle-titantic3

/assets/Clipboard_1.png
size: contain



```bash
pip install xlrd
vd titanic3.xls
```


	`shift+f` to get some stats

	`%` to make a column a number

	`!` to flag a primary column

	`.` to plot a graph

	`=` for a new column using python

---

# Irish Cars

---

# Beep Beep

	https://stats.beepbeep.ie

/assets/Clipboard_2.png
size: contain

	`d` to delete rows

	`^` to edit a column header
	`g^` to set all empty headers to current row

	`+` then `sum` to set sum on totals

	`shift+f` to get aggregates by manufacturer
	`enter` to filter by manufacturer

---

# Irish Properties

---

# House Prices 😭

	https://propertypriceregister.ie

/assets/Clipboard_3.png
size: contain

```
vd --encoding=windows-1252 PPR-ALL.csv.gz
```

	`$` for currency

- show larger dataset
- add price sum
- shift+f on desc to show data cleanliness
- group by postal code and guess which has the highest total :D
- demo filtering down to my development
    - | 

---

	# Thank You!
	https://github.com/micktwomey/visidata-talk
	@micktwomey
	@micktwomey@mastodon.ie

/assets/Clipboard_4.png
size: contain

