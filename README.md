## Testing `Vercel`, `Netfily`, `Cloudflare Pages`, `Github Pages` Deployments

This repo is available at

1. [Github Pages](htpps://github.minlaxz.me/deploy-tests) CF proxies
2. [Cloudflare Pages](https://deploy-tests.pages.dev) N/A maybe
3. [Vercel - Production](https://vercel.deploy-tests.minlaxz.me) NO CF proxies
4. [Vercel - Development](https://devel.vercel.deploy-tests.minlaxz.me) NO CF proxies
5. [Netfily - Production](https://netlify.deploy-tests.minlaxz.me) NO CF proxies

- Multiple deployments on branches
- Custom domains with SSL
- Deployment on PR to `main`

### Multiple deployments on branches

1. Vercel
2. Cloudflare auto deploys for new commit on other branch.
3. Github Pages ?

### `Custom domains with SSL`,

1. Cloudflare Pages
2. Vercel
3. Netlify, Github Pages
   (I like donate to `let's encrypt` button on Netlify for `free SSL` anyway)
   (Github pages need cloudflare proxies for `SSL`, that proxies would cause a problem for app)

### Deployment on PR to `main`

1.Netlify deploys a build on PR to `main`.

### Preview Protection

1. Cloudflare Pages
2. Vercel (paid)

For me `vercel` is a good choice.
