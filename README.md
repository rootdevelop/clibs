# clibs
Collection of useful c libs

**split.c / split.h**
Function that splits strings based on a delimiter

`int split (const char *str, char c, char ***arr);`


**vector.c / vector.h**
Vector implementation for C that allows dynamic sized vectors of strings

```
void vector_init(vector *);
int vector_total(vector *);
static void vector_resize(vector *, int);
void vector_add(vector *, void *);
void vector_set(vector *, int, void *);
void *vector_get(vector *, int);
void vector_delete(vector *, int);
void vector_free(vector *);
```

**string.h**
Typedef for string

`typedef char *string;`
