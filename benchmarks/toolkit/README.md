# Official scoring engine — build provenance

The institute distributes the official benchmark scoring engine as a compiled
extension only. This directory preserves the Cython-generated translation unit
`score_engine.c` that produced the current release build, for build provenance.

The installed package is available in the working environment at
`tools/score_toolkit/`. Published scorecards must be computed by executing the
official engine; do not estimate numbers or reuse earlier scorecards.
