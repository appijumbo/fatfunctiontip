# fat function tip for Atom

I got tired of typing fat function’s i.e. () => {}  in Atom 

typing 
```
af  [TAB]
```
works but I prefer to type {} brackets so heres how you can do just that

by adding a snippet to get a short cut

(1) In Atom open up snippets.cson
  edit → snippits

(2)  Inserted this code at top of page

```
'.source.js':
  'Fat function':
    'prefix': '()'
    'body': '($1) => {$2}'
```

and save

and hey presto, now in JavaScript can type () then press TAB key and get an ES6 fat function () => {}
