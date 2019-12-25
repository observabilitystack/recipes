# Kubernetes Observability Patterns

A collection of Kubernetes Observability, Monitoring and Log Management
patterns. This site is inspired by the excellent [recipes.rbac.dev](https://recipes.rbac.dev/)
site.

## Building the site

```
docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material
```

## Deploying the site

```
docker run --rm -it -v ~/.ssh:/root/.ssh -v ${PWD}:/docs squidfunk/mkdocs-material gh-deploy
```

## License

This repo is distributed under [MIT license](LICENSE).