# espanso search

## install

install [espanso](https://espanso.org)

```sh
cd "$(espanso path | grep Packages | awk -F ': ' '{print $NF}')"
git clone https://github.com/sayomelu/espanso-search`
```

## update

```sh
cd "$(espanso path | grep Packages | awk -F ': ' '{print $NF}')"
git pull
```

## usage

all search trigger can be found at [espanso-search/item](./item)
