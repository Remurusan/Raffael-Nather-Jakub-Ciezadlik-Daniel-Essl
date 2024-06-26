# Markdown Extension Examples

This page demonstrates some of the built-in markdown extensions provided by VitePress.

## Syntax Highlighting

VitePress provides Syntax Highlighting powered by [Shiki](https://github.com/shikijs/shiki), with additional features like line-highlighting:

**Input**

````
```js{4}
export default {
  data () {
    return {
      msg: 'Highlighted!'
    }
  }
}
```
````

**Output**

```js{4}
export default {
  data () {
    return {
      msg: 'Highlighted! AnToN HorVAtH war HIER OIDAAAAc !'
    }
  }
}
```

## Custom Containers

**Input**

```md
::: Hallo
Hallo das bin ich
:::

::: tip
This is a tip.
:::

::: warning
This is a warning.
:::

::: danger
This is a dangerous warning.
:::

::: details
This is a details block.
:::
```

**Output**

::: info
Das ist keine Info.
:::

::: tip
Tipp 4 Tipp dir den Kick.
:::

::: warning
Keine Angst.232
:::

::: danger
Gefahr.
:::

::: details
Detail Block this is.
:::

## More

Check out the documentation for the [full list of markdown extensions](https://vitepress.dev/guide/markdown).
