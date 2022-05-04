# waldl

Browser [wallhaven](https://wallhaven.cc/) using `nsxiv`

### [script showcasing video](https://youtu.be/C7n-34bEdF8)


## Usage
```
waldl <query>
```
> Leave query empty to use `dmenu`

- Select wallpapers by marking them using `m` in `sxiv`.
- Quit `nsxiv` using `q`.

Selected images would be downloaded. The default download directory is

	~/pics/wall/

Defaults can be changed by changing the user variables, in the start of the
script.


## Dependencies

* nsxiv
* jq
* curl
* dmenu ( *optional* )


