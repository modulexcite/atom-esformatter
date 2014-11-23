# esformatter

[Atom package](https://atom.io/packages/esformatter)

> Beautify JavaScript using [esformatter](https://github.com/millermedeiros/esformatter)

<img src="https://cloud.githubusercontent.com/assets/170270/4490970/2333d93a-4a33-11e4-9954-dffea0c5f528.gif" width="311">

*Issues with the output should be reported on the esformatter [issue tracker](https://github.com/millermedeiros/esformatter/issues).*


## Install

```sh
$ apm install esformatter
```

Or Settings → Packages → Search for `esformatter`


## Usage

Open the Command Palette, and type `esformatter`.

Can also be run on just a selection. For example the code in a `<script>` tag.

There's a `Format On Save` option in the Settings.


## [Config](https://github.com/millermedeiros/esformatter#configuration)

Some [plugins](https://github.com/sindresorhus/atom-esformatter/blob/7ff87d550b880d14840bbee6d6c4cbfbb1b57016/package.json#L22-L28) are bundled. *PR welcome for more.*

Just add the ones you want to your config file:

```json
{
	"plugins": [
		"esformatter-braces"
	]
}
```


## License

MIT © [Sindre Sorhus](http://sindresorhus.com)
