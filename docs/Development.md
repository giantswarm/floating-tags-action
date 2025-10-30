# Development

To update dependencies and update `./dist` run the following commands.

**Note:** If you use `nvm` to manage NodeJS locally, make sure to select the major version used by the repository. See `actrion.yml` for the right version.

```bash
# Install yarn
npm install -g corepack
yarn set version stable

# Install dependencies
yarn install

# Check code
yarn lint

# Create packaged JS file
yarn dist
```
