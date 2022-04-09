## NOTES

update book to github

- mdbook build
- cp -r build dist
- commit...
- push dis to master branch

  ```shell
  git push origin `git subtree split --prefix dist master`:master --force
  ```
