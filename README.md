leanTAP: A Theorem Prover for First-Order Classical Logic
=========================================================

This project implements leanTAP in clojure.core.logic.nominal closely
following the alphaleanTAP implementation described in
_alphaleanTAP: A Declarative Theorem Prover for First-Order Classical Logic_
([PDF](http://www.cs.indiana.edu/~webyrd/alphaleantap/alphatap.pdf))
and chapter of 10 of
[William Byrd](http://www.cs.indiana.edu/~webyrd/)'s thesis
([PDF](http://gradworks.umi.com/3380156.pdf)).

The
[`alphaleantap`](https://github.com/namin/leantap/tree/master/alphaleantap)
directory contains the original implementation in Scheme.

The [`cljtap`](https://github.com/namin/leantap/tree/master/alphaleantap)
directory contains the implementation in Clojure.

Statistics
-----------------------------------

On the Pelletier problems, the Clojure implementation is roughly 1/3
faster on average than the original implementation tested with Petite
Chez Scheme.

<img src="https://docs.google.com/spreadsheet/oimg?key=0Aq6lPvMWlyvwdGRtbDRYZGpmcXI1OG9RM2swNWxyc1E&oid=2&zx=oejhl3v763go" />
