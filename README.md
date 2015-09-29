# nginx

Forked from http://anonscm.debian.org/cgit/collab-maint/nginx.git/

## Maintaining

Clone the repository and initialize all submodules:

```
git clone --recursive https://github.com/freeletics/nginx.git
```

Add the upstream repo as a remote:

```
git remote add upstream git://anonscm.debian.org/collab-maint/nginx.git
```

Pull changes from master:

```
git checkout master
git pull upstream master
```

Merge master to custom branch:

```
git checkout freeletics
git merge master
```
