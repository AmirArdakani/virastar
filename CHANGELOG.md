### 0.15.0
- Added: support prefix: `bi*`, props @zoghal
- Added: support suffix: `*am`, `*at`, `*ash`, `*ei`, `*eid`, `*eem`, `*and`, props @zoghal
- Added: support suffix: `*hayee`, `*hayam`, `*hayat`, `*hayash`, `*hayetan`, `*hayeman`, `*hayeshan`, props @zoghal
- Fixed: check for space befor suffix: `*tar`, `*tari`, `*tarin`, props @zoghal

### 0.14.0
- Added: convert back quot/apos entities
- Added: new option: `decode_htmlentities`
- Fixed: test suite

### 0.13.0
- Added: [coding standard](https://github.com/Flet/semistandard)
- Added: passing options directly into cleanup method

### 0.12.0
- Added: new option: `preserve_brackets`
- Added: new option: `preserve_braces`

### 0.11.0
- Added: new option: `kashidas_as_parenthetic`
- Fixed: remove all kashida between non-whitespace characters

### 0.10.0
- Added: new word tokenizer detection
- Added: skip english numbers conversion in html entities
- Added: bower integration
- Fixed: multiline flag on begin/end cleanup