# janus-plugins
A repository containing Vim plugins that I use to customize the [Janus Vim Distribution](https://github.com/carlhuda/janus)

# Installation

```shell
git clone --recursive git@github.com:milkfarm/janus-plugins.git ~/.janus
```

# Update plugins

```shell
cd ~/.janus
git submodule update --init --recursive
```
  
# Add plugin

```shell
cd ~/.janus
git submodule add git@github.com:USER/REPO.git
git commit -am "Add REPO plugin as submodule"
```
