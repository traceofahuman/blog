# Traceofahuman Simple Blog Site

## Setup:
___
1. Build the Static Site: GoHugo
2. Provide Contents: A separate repository for content creation and editing, e. g. using Obsidian, imported as Golang Module 
3. Deploy Static Site: Github Pages
4. Update Static Site using Github Actions:
    - [Receive Dispatch and Rebuild Hugo Page](https://github.com/traceofahuman/blog/blob/main/.github/workflows/hugo.yaml)
    -  [Fire Dispatch Event](https://github.com/traceofahuman/vault/blob/main/.github/workflows/hugo-dispatch.yml)

## Credits:
- https://github.com/gohugoio/hugo
- https://github.com/hugo-sid/hugo-blog-awesome
- https://github.com/peter-evans/repository-dispatch
- https://github.com/jmooring/hugo-module-content
