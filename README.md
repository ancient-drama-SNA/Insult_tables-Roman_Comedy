# Roman Comedy — Insult Interactions

Data on insult interactions among characters from the plays of Plautus and Terence. Collated
by hand, and (currently) put into CSV format.


## 'Insult Tables' notes:

* As currently set up, the tables are encoded as CSV files.
    - The delimiter for each field is a comma.
    - Each has a 5-line header, which contains metadata.
    - Lines 1–3 are metadata related to the textual edition, and so on.
    - Line 4 is blank (separator).
    - Line 5 contains the column headers (= category labels).
    - If converted to e.g. JSON or some other format, header lines 1–4 need to be stripped.
      Line 5 should remain.
* For conversion, the `csvtojson` command-line tool seems to work well. (A `node` program.)
    - BUT: only works if the header/metadata is removed.


## Project Goals

* These tables began as nothing more than handy records for reference while writing my
  monograph. However they should be useful for a more formal (and sophisticated) analysis down
  the road.
* Once each play is analyzed and insult interactions are compiled, I hope to accomplish the
  following:
    1. Convert each table into a JSON document, for use in computer analysis.
    2. Develop a methodology for analyzing insult interactions within corpora using the
       encoded data. E.g., both within individual plays, but also across the Plautine and
       Terentian corpora.
    3. Document and extend the workflow for use with other dramatic corpora.
    4. ???


## Progress:

- [ ] Amphitruo
- [x] Asinaria 
- [ ] Aulularia
- [ ] Bacchides
- [ ] Captivi
- [ ] Casina
- [ ] Cistellaria
- [ ] Curculio
- [ ] Epidicus
- [ ] Menaechmi
- [ ] Mercator
- [ ] Miles Gloriosus
- [ ] Mostellaria
- [ ] Persa
- [ ] Poenulus
- [ ] Pseudolus
- [ ] Rudens
- [ ] Stichus
- [ ] Trinummus
- [ ] Truculentus
- [ ] Vidularia
