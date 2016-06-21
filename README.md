Steps to reproduce the bug:

```bash
npm install
npm run lint
```

Result:

```txt
test.less
 11:9   ✖  Unexpected extra semicolon   no-extra-semicolons
 20:13  ✖  Unexpected extra semicolon   no-extra-semicolons
 25:11  ✖  Unexpected extra semicolon   no-extra-semicolons
```

Expected result: no errors
