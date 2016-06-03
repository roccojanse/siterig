# SiteRig
SiteRig is a website starter kit

SiteRig makes use of third party gems, managed by Bundler. To install Bundler (if you haven't done so) run:

```bash
gem install bundler
```

Windows users, if you have trouble compiling due to line endings then make sure
you configure git to checkout the repository with `lf` (unix) line endings. This
can be achieved by setting `core.eol`.

```bash
git config core.eol lf
git config core.autocrlf input
git rm --cached -r .
git reset --hard
```

## Initial install

```bash
npm install
bundler install
```