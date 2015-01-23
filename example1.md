---
---

I am trying to achieve both these objectives with one relative link:
- [ ] A. Link from <http://_playground.wikihydra.com/example1> to <http://_playground.wikihydra.com/test1>  
- [ ] B. Link from <https://github.com/WikiHydra/_playground/blob/gh-pages/example1.md> to <https://github.com/WikiHydra/_playground/blob/gh-pages/test1.md>

#### Works with Jekyll (A), breaks with Github 
`[test1](test1)`
[test1](test1)

#### Breaks with Jekyll, works with Github (B)
`[test1](test1.md)`
[test1](test1.md)




