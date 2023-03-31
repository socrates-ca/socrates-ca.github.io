# socrates-ca.github.io [![CI](https://github.com/socrates-ca/socrates-ca.github.io/actions/workflows/main.yml/badge.svg)](https://github.com/socrates-ca/socrates-ca.github.io/actions/workflows/main.yml)

## How to contribute ?

The site is build with [Hugo](https://gohugo.io/) and the content is in [config.toml](config.toml).

Make a PR on the branch `hugo` not on branch `master`.

## Run the site locally

### Pre-requisite: Install Hugo

We use Hugo version 0.83.1.

To install this specific version, download the appropriate tarball: https://github.com/gohugoio/hugo/releases/tag/v0.83.1

Unpack it the downloaded tarball. For instance:

```
tar -xvzf $HOME/Downloads/hugo_extended_0.83.1_macOS-64bit.tar
```

Then, move the `hugo` binary to your bin directory. For example:

```
mv hugo /usr/local/bin
```

_If you aren't sure which path to use, run `echo $PATH` to find which path can be used to execute the Hugo binary._

You can check it's working by running `hugo version`.

#### "I use MacOS and the `hugo` command doesn't work!"

If you are on MacOS, it may complain that it's not secure and won't execute it. In this case:

1. Reveal the file in the Finder (`open /usr/local/bin`)
2. Right-click the hugo script
3. Select "Open" and tell MacOS it's fine to execute

Once done, you can execute the command again.

### Run the server

```shell
hugo server
```

This should serve the website on http://localhost:1313/

To simply build the site locally:

```shell
hugo
```

### Continuous Delivery

When a PR (on the branch `hugo`) is merged, [GitHub Actions](https://github.com/socrates-ca/socrates-ca.github.io/actions) is triggered to build and deploy automatically the site.
