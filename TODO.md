## todo

- [ ] write the book — according to [outline](outline.md) and at heads below
- [ ] standardization
	- [ ] **Write README and outline**
	- [ ] Standardize everything in [lore](lore.md) including  r̥ ṁ, and make the changes throughout the book
	- [ ] Standardize quotation formats and italics (in flashback chapters, [full_page_vizhdam](chapters/specials/quotes/full_page_vizhdam.md))
	- [ ] Em dash en dash
	- [ ] Spell check
- [ ] simple tasks
	- [ ] try replacing the “Magadha culture” stuff with something else, maybe Vrātyas or something e.g. [3.9](chapters/3/3.9.md). Also emphasize caste less, it’s a bit putting-off.
	- [ ] Remove excessive boomer words like *civilization* and *culture*
	- [ ] try to reflect that the Persian acquisitions in India were only brief and temporary (see [never_invaded](chapters/specials/quotes/greek.md#never_invaded)) — also reduce the prominence of Sindh in the book, it was a relatively small region back then
	- [ ] write travel scenes better, reflecting a caravan scene — though can still point out that trade had stalled due to Nanda neglect of infrastructure etc.
	- [ ] the two visitors in the prologue should be messengers not professors
	- [ ] probably remove the stupid humour attempt calling Seleucus fat [3.12](chapters/3/3.12.md) — oh, I also called some student’s mother fat [1.10](chapters/1/1.10.md)
	- [ ] add bit about buying female guards from the Greeks
- [ ] big tasks
	- [ ] write female characters better — Yaśomatī, Puṣkaradhāriṇī, Ghr̥tācī. What are some genuinely well-written female characters in literature?
	- [ ] add images

## heads

Heads where writing is to be appended

- [ ] **insert stuff about Alexander’s supply route being cut off**
![3.4](chapters/3/3.4.md#^fgvrl8)
- [ ] **this is weird. And should include more specifics**
![3.5](chapters/3/3.5.md#^zvwwbt)
- [ ] **this whole excerpt doesn’t really make sense, get a better reason for Sakadala to get suspicious**
![3.8](chapters/3/3.8.md#^7407x4) 
- [ ] **main head, where writing should be continued:**
![4.2](chapters/4/4.2.md)

## compilation notes
things to keep in mind while writing a script to compile
1. date formats
2. embeds, including quote embeds
3. full page vizhdam quotes
4. chapter titles
5. line spacings esp. at the start and end of embeds and chapters

### formats

Date formats should be given e.g.

```
[date:-340|magadha,“but in the sleepy Southern city of Pratiṣṭhāna”,x]
```


- `-340` is the Christian year (340 BC)
- `magadha` indicates that the year in Magadha hegemony (i.e. years from its epoch 492 BC) should be given
- `“but in the sleepy Southern city of Pratiṣṭhāna”` is custom text to be added
- `x` indicates that the year in Christian calendar should be given

Before compiling, run a script to compile dates. The above example should ideally be rendered as:

```
<center>
In the 152nd year of Magadha hegemony
<br><br>
but in the sleepy Southern city of Pratiṣṭhāna
<br><br>
(340 BC)
</center>
```

Calendar format standards:

- magadha
- x
- age_canakya
- flashback (counted from the last-mentioned non-flashback date)