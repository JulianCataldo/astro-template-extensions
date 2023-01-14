# Astro — Template Extensions (Web Components proposal)

An AstroJS adaptation of the [Template Extensions](https://github.com/luwes/template-extensions) examples.

```
pnpx degit https://github.com/JulianCataldo/astro-template-extensions astro-te-demo
cd astro-te-demo && pnpm i && pnpm dev
```

See the [live demo](https://juliancataldo.github.io/astro-template-extensions).

See also [custom-elements-ssr](https://github.com/thepassle/custom-elements-ssr#readme), could be explored for isomorphic template strings bindings + rendering, with an AstroJS renderer.

# Notes

- We can escape template strings variables with `{'{{ var }}'}` or `is:raw` Astro directive.
