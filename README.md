<div align="center">
  <img src="https://eu-images.contentstack.com/v3/assets/bltdb98d8f2fea905ea/bltca7bb30bdca5a943/ParkHolidaysUKLogo"/>
</div>

# Legal

> Tracked legal documentation for Park Holidays UK websites

This repo contains all of the legal documents for Park Holiday's websites.

## Guidelines

- All documentation should be written in standard
  [markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- Websites should load from the `main` branch directly by using
  `https://raw.githubusercontent.com/park-holidays-uk/legal/main/[filePath]`,
  where `[filePath]` is the path to the file within the repository.
- A Markdown loader can be used to automatically format the contents.
- YAML-style [frontmatter](https://markdoc.dev/docs/frontmatter) should be used
  to provide metadata about the document, including the last updated date, and
  page meta information.

## Branching

While the new website project is underway, we should maintain 2 branches of this
repo.

- `master` - The branch that existing sites link to. Will eventually be
  deprecated.
- `main` - The new primary branch that new sites should link to. The structure
  has been updated to match the new sites, and allow for branding placeholders
  for re-use across brands.

## Site Structure

- `archive` - Archived data that is no longer required, stored in the last state
  it was in. The `archive` should also contain the folders listed below and keep
  the files in the same structure so that the only difference is that the
  `[filePath]` has `archive/` prepended to it.

## Placeholders

To allow for re-use, documentation can be written with additional placeholders
that can be updated based on the brand of the website, allowing the same content
to be used for multiple brands, without needing to be duplicated. The replacer
values are stored in the [branding.json](./branding.json) file.

<!-- TODO: Structure/Usage needs sorting -->
