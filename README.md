# Frozen Pizza Studios Website

## Quick Start
- Install [Git LFS](https://git-lfs.com/) and run `git lfs install`
- Install [Zola](https://www.getzola.org/documentation/getting-started/installation/)
- `zola serve --open` to preview the site locally as you work

## Post Formatting
- Posts should be named `YYYY-MM-DD-title.md` and have `title` and `taxonomies` front matter at a minimum
- Either an explicit `description` front matter should be provided, OR a `<!-- more -->` comment should be placed within the content.  The latter is how Zola automatically generates page summaries, but I've had trouble getting it to work when placed mid-line.
