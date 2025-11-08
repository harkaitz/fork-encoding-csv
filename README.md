# ENCODING/CSV (+) 

A better encoding/csv for go with bug fixes.

The following are supported by `encoding/csv(+)` but not by the `encoding/csv`
in the standard library.

    Trailing whitespace:   field1,   "field2"[   ], field3

Replace the `encoding/csv` in your imports with:

    import (
    -        "encoding/csv"
    +        "github.com/harkaitz/fork-encoding-csv"
    )

