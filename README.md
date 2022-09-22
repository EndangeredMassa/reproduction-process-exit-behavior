# Reproduction: consuming code's process exit behavior modified

To reproduce:

- clone
- `npm install`
- `node index.mjs`
- `echo $?`

You will not see the expected error message thrown from `index.mjs`.

You will see an exit code of `0` instead of `1`.
