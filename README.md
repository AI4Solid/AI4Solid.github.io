# AI4Solid website

The organization website is a static GitHub Pages site. Configure Pages to deploy from `main` and `/(root)`.

LeanSolid publishes independently from its own [repository](https://github.com/AI4Solid/LeanSolid), using GitHub Actions to deploy its `website/` directory. Both sites ship a local copy of the same stylesheet so either repository can deploy independently. Coordinate changes to the navigation and stylesheet in both repositories.

To add an active project, publish it from its own repository, add its link to the organization site, and list its sitemap in `robots.txt`.
