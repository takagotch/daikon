### daikon
---
https://github.com/codespecs/daikon

https://plse.cs.washington.edu/daikon/

```cc
// tests/daikon-tests/Daikon/Makefile
mkfile_path := $(abspath $(lastword $(MAKEFILE_LIST)))
current_dir := $(notdir $(patsubst %/,%$(dir $(mkfile_path))))

ESC_ON:=1
INSTRUMENT:=infer
SOURCES:=$(current_dir)../../../java

INPUTS_DECLS:=$(PWD)/inputs/print_tokens2.decls
INPUTS_DTRACE1:=$(PWD)/inputs/print_tokens2.1.dtrace.gz
```

```
```

```
```
