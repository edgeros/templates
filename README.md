# EdgerOS project templates

Templates to be used by [EdgerOS VSCode Extension](https://marketplace.visualstudio.com/items?itemName=edgeros.edgeros)
and `@edgeros/cli` the npm package.

Here we list each template as a folder, which should contain:

### banner.png
An icon/banner image to be shown in the VSCode Extension template list

### desc.json
Template metadata description

- `type`: only "Base" for now
- `repository`: either a string starts with 'https://github.com/' or an object which contains:
  - `github`: github repo url is *always* required
  - `gitee`: optional and alternative gitee repo

``` JSON
{
  "name": "tpl-simple",
  "description": "Very basic and simple project template",
  "type": "Base",
  "repository": {
    "github": "https://github.com/edgeros/tpl-simple.git",
    "gitee": "https://gitee.com/edgeros/tpl-simple.git"
  }
}
```

## Pull Request is appreciated !!
