# fat function tip for Atom

Atom tip :
I got tired of typing fat function’s i.e. () => {}  in Atom
So I’ve added a snippet to get a short cut

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

and hey presto, now in JavaScript can type () then press TAB key and get a n ES6 fat function () => {}
