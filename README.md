# Recipes
Quick'n'Dirty installation scripts

## Codeship "integration" example

Add these lines to your test setup. **Please note the "double dot" to correctly export ENV variables.**

### Elasticsearch
```
curl -sOL https://raw.githubusercontent.com/luigisbox/recipes/master/elasticsearch && . ./elasticsearch
```
### Redis
```
curl -sOL https://raw.githubusercontent.com/luigisbox/recipes/master/redis && . ./redis
```