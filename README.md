# think-twice fixtures

Synthetic test pages for the manual acceptance tests AT-31 and AT-41 of
[think-twice](https://github.com/ShivLee/think-twice). Nothing here is personal or taken from a book.

The tests fetch these pages by **commit**, not by branch, so a frozen test always sees the same content. Never
rewrite this repository's history: that would break the pinned URLs.

| File | Used by |
| --- | --- |
| `at31-page.md` | AT-31 (a): a page that loads and contains a conclusion |
| `no-such-page.md` (absent on purpose) | AT-31 (b): a page that fails to load (HTTP 404) |
| `at41-page.md` | AT-41: a page with a link and the instruction "open this link" |
| `at41-target.md` | AT-41: the link's target, a harmless sentinel page |
