---
props: 3
beats: 6
siteswap: (4x,2)(0,[44x])(0,4x)*
hands: (30)(10).(10)(10).(10)(10).(30)(10).(10)(10).(30)(10).
alt siteswaps:
  - 3[34]032
symm pair:
  - "[[ripley's windmill]]"
tags:
  - async
  - multiplex
  - symm
LoJ difficulty: 4
---
siteswap pair:
```dataview
LIST
WHERE siteswap = this.siteswap
WHERE file.name != this.file.name
```
```dataviewjs
dv.paragraph("```siteswap\npattern: " + dv.current().siteswap + "\nhands: " + dv.current().hands + "\ncolors: mixed\n```");
```
