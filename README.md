# extend-placeholder-with-parent-reference-sass
https://github.com/sass/dart-sass/issues/1066
## Steps
1. Run `npm install` or `yarn`
2. Run `npm run compile-via-node-sass` or `yarn compile-via-node-sass`
```
.foo, .bar.foo {
  color: red; }
```
3. Run `npm run compile-via-dart-sass` or `yarn compile-via-dart-sass`
```
.foo {
  color: red;
}
```
## Result
`.bar.foo` is missing.