# First Mysql UDF

# UDF Repository for MySQL

## Extend your MySQL server with additional functions

Sample repository to extend MySQL server by develop additional function. (MySQL UDF)

### Compiling

```
gcc -shared -o mcalc.so mcalc.cc
cd sql
make mcalc.o
```

### Installing module

```sql
CREATE FUNCTION mcalc RETURNS STRING SONAME "mcalc.so";
```

### Uninstalling module

```sql
DROP FUNCTION mcalc;
```

---------

# Max Base

My nickname is Max, Programming language developer, Full-stack programmer. I love computer scientists, researchers, and compilers.

## Asrez Team

A team includes some programmer, developer, designer, researcher(s) especially Max Base.

[Asrez Team](https://www.asrez.com/)
