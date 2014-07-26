# &lt;freebase-search&gt;

> Web Component wrapper to the [Freebase API](https://developers.google.com/freebase/), that allows you to search on Freebase (a large collaborative knowledge base) using [Polymer](http://www.polymer-project.org/).

## Demo

[Check it live!](http://cesarwbr.github.io/freebase-search/)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install freebase-search --save
```

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/freebase-search/dist/freebase-search.html">
    ```

3. Start using it!

    ```html
    <freebase-search></freebase-search>
    ```

## Options

Attribute  | Options        | Default             | Description
---        | ---            | ---                 | ---
`domain`   | *string*       |                     | Specifies the [Freebase Domain](https://developers.google.com/freebase/guide/basic_concepts#domains), eg: `/business`, `/music`, `/film`, `medicine`...
`lang`     | `en`, `es`, `fr` , `de`, `it`, `pt`, `zh`, `ja`,`ko`, `ru`, `sv`, `fi`, `da`, `nl`, `el`, `ro`, `tr`, `hu`, `th`, `pl`, `cs`, `id`, `bg`, `uk`, `ca`, `eu`, `no`, `sl`, `sk`, `hr`, `sr`, `ar`, `hi`, `vi`, `fa`, `ga`, `iw`, `lv`, `lt`, `gl`, `is`, `hy`, `lo`, `km`, `sq`, `fil`, `zxx`    | `en`    | Specifies the language to be used in the search and results.
`limit`    | *number*       | `4`                 | Specifies the number of results on search.


### Events

Event      | Description
---        | ---
`onresult` | Triggers when the user choose one result on the typeahead list.

## License

[MIT License](http://opensource.org/licenses/MIT)
