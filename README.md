### Remove duplication lines:
```regex
^(.*?)$\s+?^(?=.*^\1$)
```

### Remove lines included in filter text:
```regex
^(?!.*(http|host_painel|reclo).*).*$
```
