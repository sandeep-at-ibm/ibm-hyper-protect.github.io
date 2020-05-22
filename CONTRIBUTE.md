# How to Contribute
We accept suggestions, ideas, and code! To start a discussion, please
raise an issue.

To create a Pull Request (PR):

- Fork this repo
- Clone and edit locally
- Locally test your changes (see below)
- Submit a PR

After review, we will consider and potentially accept changes into the
`develop` branch, merged occasionally into `master`, from which the
site is built.

Please locally test your changes before you submit a PR. We find this
Docker image works well for this purpose. From the directory where
you've cloned your git repo:

```bash
docker run -it --rm -v "$PWD":/usr/src/app -p "4000:4000" starefossen/github-pages
```

then open a web browser at
[localhost:4000](http://localhost:4000). Please raise an issue if you
find problems with the site.
