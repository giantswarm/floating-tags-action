# Development

To update dependencies and update `./dist` run the following commands.



```bash
alias y="docker run -it --rm --platform linux/amd64 --name my-yarn-project -v '${PWD}:/usr/src/app:Z' -w /usr/src/app node:24-slim yarn"

# Install dependencies
y install

# Check code
y lint

# Create packaged JS file
y dist
```
