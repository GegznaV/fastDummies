# fastDummies 1.2.0

* Adds option to exclude the most frequently observed category rather than the first
    category as is default. Thanks to GitHub user S-UP for the suggestion!

# fastDummies 1.1.0

* Thanks to GitHub user yu45020 dummy_cols() is now about >20% faster
    and much more memory efficient.

* Both dummy_cols() and dummy_rows() now return the same data type inputted
   + e.g. data.frame input returns data.frame, tibble returns tibble.
   
* Fix documentation that incorrectly said default value for new dummy rows
is 0. It is in fact a value of NA.

# fastDummies 1.0.0

* Reduces number of parameter that were in previous version.

* Significant speed increases for both dummy_cols() and dummy_rows() functions.

* dummy_cols() now accepts numeric columns.



