# GitHub Actions Template

A template for a GitHub Action using a Node.js script with Webpack

## Dev Setup

```shell
yarn
yarn build # builds the uncompiled JS to the `lib` folder
```

Be make sure to commit the `lib` folder as that is the location of the entrypoint for the action.

## Usage

```yaml
steps:
  # ...
  - name: My new GitHub Action
    uses: lannonbr/github-action-template@v1
    with:
      name: Benjamin
```
