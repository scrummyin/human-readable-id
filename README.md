[![N|Solid](https://repository-images.githubusercontent.com/324334992/6016fe00-4882-11eb-8824-68c825521965)](https://github.com/hnimminh/human-readable-id)


<p  align="center">
  <strong>HRID: Human Readable Identifier</strong>
  <br>
  <code>The Human Readable ID Generator Library For Python3</code>
  <br>
</p>

## Usage

Install
```
pip3 install hrid
```

Use in Python code
```python
from hrid import HRID

hruuid = HRID()
uuid = hruuid.generate()
print(uuid)
```

## Why HRID ?
* Comapareing to UUID, it's extremely easy to remember, that why this package named `human readable`, example `red-bird-fly-crazily` versus `206dbaab-526b-41cd-aa6f-7febd82e83ab`. 
* Over 800 bilions alphabet uuid can be generated by default (or many more if include more element). In the other hand, this library can guarentee that rarely, the uuid will be generated twice .
* Customizable structure for uuid, eg {`adj`}{`noun`} or {`number`}{`adj`}{`noun`}{`verb`}{`adverd`} or add whatever you want `prefix`, `postfix`

## Credit
* [Dictionary Source](https://github.com/dariusk/corpora)
* [Inspired by Google API Design](https://cloud.google.com/blog/products/gcp/api-design-choosing-between-names-and-identifiers-in-urls)

## License

[MIT](./LICENSE)