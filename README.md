# siarid

Some (mainly python) code to create Simple Article Identifiers as
PhRvL-Martin2021ase for "A Simple Explanation for ..., Max Martin and al, Phys. Rev. Letters (2021)"

The paper part (here PhRvL) is [SAO/NASA Astrophysics Data System](https://ui.adsabs.harvard.edu/adbout) acronym.

- data/001.txt contains 387 lines like `PhRvL = Phys. Rev. Lett.`
- data/s001.txt contains 387 lines like `PhRvL = Phys. Rev. Lett.`, sorted by key
- data/002.txt contains 1740 lines like `Physical Review Letters = Phys. Rev. Lett.`
- data/003.txt contains 50 lines like nothing precise
- data/004.txt contains 3436 lines like `    PhRvL        Physical Review Letters` with some header lines. A copy of one of [these files](https://www.google.com/search?q="ADS+Bibliographic+Codes%3A+Refereed+Publications").
- data/101.txt contains 3850 lines like `PhRvL = Physical Review Letters`
- data/s101.txt contains 3850 lines like `PhRvL = Physical Review Letters`, sorted by key

