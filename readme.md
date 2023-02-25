# Resume

My resume based on [JSON resume schema](https://jsonresume.org/schema/)
## Usage
* `npm run build-LANG` builds a `resume.json` file using partials from `parts/`
* `npm run watch-LANG` builds, watches and serves an html version of the resume. Ideal for developmnent purposes.
  You can pass addition arguemnts to the `serve` command appending them to the end.
  For example, to use a local theme, use `-- --theme ./YOUR_LOCAL_THEME`
  ```
  npm run watch-LANG -- --theme ./YOUR_LOCAL_THEME
  ```
## Changelog
### 2021-08-15
* Add `url` as alternative to `website` for all sections
* Add `name` as alternative to `company` in `work`
* Add `score` to `education` items
* Add `url` to `awards`. This is an unofficial schema field
* Add `location` to `work` items. Unofficial field
* Add ES translation to most sections
* Reorder sections and items
### 2020-09-01
* Initial commit
