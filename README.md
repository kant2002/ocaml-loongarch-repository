```
opam repo add loongarch https://github.com/kant2002/ocaml-loongarch-repository.git
```

This will add the beta remote as a non-default extra source of opam packages. You can then create a compiler switch to the trunk compiler by:

```
opam switch create 408 ocaml-variants.5.1.0+loongarch --repositories=default,loongarch
```
