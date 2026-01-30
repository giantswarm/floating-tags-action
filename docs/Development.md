# Development

To update dependencies and update `./dist` run the following commands.



```bash
alias yarn="docker run -it --rm --name my-yarn-project -v '${PWD}:/usr/src/app:Z' -w /usr/src/app node:24-slim yarn"

yarn install && yarn lint && yarn dist
```
