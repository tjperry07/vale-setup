# Test File

There are 4 checks happening:

1. Vale - https://github.com/errata-ai/vale-action Checks aganist the style guide files found in .github folder. This action is wrapped in another action so it only checks modified files.
2. Mardown Link Check https://github.com/gaurav-nelson/github-action-markdown-link-check#check-multiple-directories-and-files. Checks files for broken links. Can also be run on a schedule and configured to ignore links.
3. Image Actions - https://github.com/calibreapp/image-actions Compresses your images and creates a new PR with the compressed images.
4. Super Linter - https://github.com/github/super-linter All the linters in one. Just running the markdown one. It can be configured to check certain rules
