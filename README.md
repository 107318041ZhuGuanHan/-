```flow
st=>operation: ...
e=>end: End
opyes=>operation: Yes Operation
opno=>operation: No Operation
cond=>condition: Yes or No?

st->cond->
cond(yes)->opyes->e
cond(no)->opno->e
```
