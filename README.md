# Repro for bad --fix behavior with allowAutomaticSingleRunInference

To reproduce, run:

```
npm install
npm run lint
```

Check out any of the `index*.ts` files, they will be mangled.