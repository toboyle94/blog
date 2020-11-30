# Late Bus

Simple jekyll blog forked from (sidey)[https://github.com/ronv/sidey]

## Local development

Using `rbenv` to manage ruby version is helpful. Run the following to ensure the current shell
is using the ruby version specified by `rbenv`:
```
rbenv init
```

To run the site locally use:
```
bundle exec jekyll serve
```

## Deploying the site

Netlify is configured to build and deploy the site whenever there is a new commit to the
`master` branch of this git repo. To deploy a new set of changes to the site, either merge
a PR into `master`, or commit to `master` and push to git.
