# sqlite3.ProgrammingError: Incorrect number of bindings supplied. The current statement uses 1, and there are 22 supplied.

While I was working with sqlite and python where my task was to remove the certain row by query one of the column of that row

I provided the raw query and the value using above fuction
  https://gist.github.com/SurendraTamang/87a1d1d514dd4a4e302905c6f4a841f8
  
I forgot to add the comma on values tuple which was causing the error. I solve by adding the comma :)
