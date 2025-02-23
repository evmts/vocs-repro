This is a [Vocs](https://vocs.dev) project bootstrapped with the Vocs CLI.

➜  node-docs git:(main) bun run build
$ vocs build

  [building] vocs@v1.0.0-next.20250222T235036

⠙ building bundles...
node:internal/fs/promises:1033
  const result = await PromisePrototypeThen(
                 ^

Error: ENOENT: no such file or directory, stat '/Users/williamcory/node-docs/node_modules/.pnpm/vocs@1.0.0-next.20250222T235036_@types+node@22.13.5_@types+react@19.0.10_acorn@8.14.0_jiti@2._4sqxccgyfihtafxd6pq3b277ay/node_modules/vocs/_lib/app/styles/base.css.js.vanilla.css'
    at async Object.stat (node:internal/fs/promises:1033:18)
    at async C.addBuildDependency (file:///Users/williamcory/node-docs/node_modules/.pnpm/@tailwindcss+vite@4.0.8_vite@6.1.1_@types+node@22.13.5_jiti@2.4.2_lightningcss@1.29.1_yaml@2.7.0_/node_modules/@tailwindcss/vite/dist/index.mjs:1:5226) {
  errno: -2,
  code: 'ENOENT',
  syscall: 'stat',
  path: '/Users/williamcory/node-docs/node_modules/.pnpm/vocs@1.0.0-next.20250222T235036_@types+node@22.13.5_@types+react@19.0.10_acorn@8.14.0_jiti@2._4sqxccgyfihtafxd6pq3b277ay/node_modules/vocs/_lib/app/styles/base.css.js.vanilla.css'
}

Node.js v22.4.1
error: script "build" exited with code 1
➜  node-docs git:(main)

