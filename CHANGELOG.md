# Change Log

## 2015-04-06
- Removed `make_modified` feature and corresponding `g:neomake_make_modified` setting.
- You can now use the `|` to do a command after neomake: `:Neomake | echo 'something else'`.
- Don't run more than one job for a maker at any given time.