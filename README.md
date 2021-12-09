# baania.github.io

## Initial setup
```bash
git clone $REPO
git submodule add git@github.com:baania/hugo-PaperMod.git themes/PaperMod
git submodule update --init --recursive
```

## Update theme
```bash
git pull --recurse-submodules
```

## Create a new post
```bash
./create-post.sh -n $TITLE -t $TAG
```
