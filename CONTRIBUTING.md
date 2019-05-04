# Contributing

Check out ways to contribute to Open Material Components:

## Existing components: we love pull requests ♥
Help out the whole open material community by sending your merge requests and issues.
Check out how to set it up:

Setup:
```bash
# Clone the repo:
git clone https://github.com/open-material-components/open-material-components.git
cd open-material-components

# Install dependencies
yarn install

# Create a branch for your changes
git checkout -b fix/buttonSize
```

Make sure everything works as expected:
```bash
# Linting
npm run lint

# Tests
npm run test

# Storybook Demo
npm run storybook
```

Create a Pull Request:
- At https://github.com/open-material-components/open-material-components click on fork (at the right top)
```bash
# add fork to your remotes
git remote add fork git@github.com:<your-user>/open-material-components.git

# push new branch to your fork
git push -u fork fix/buttonSize
```
- Go to your fork and create a Pull Request :)

Some things that will increase the chance that your merge request is accepted:

* Write tests.
* Write a [good commit message](https://www.conventionalcommits.org/).
