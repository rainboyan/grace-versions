# Grace Versions

Inspired by the [grails-versions](https://github.com/erichelgeson/grails-versions) of Eric Helgeson who has archived his project.

But Grace can generate all versions of Grails and Grace in one CLI, so you can just do it like this,

```
grace create-app app.versions \
      --grace-version=2023.0.0 \
      --version-prev=2022.1.0,2022.2.0 \
      --version-next=2023.1.0,2024.2.0 \
      --template ./scripts/generator.groovy \
      --force --enable-preview
```

Handy repo/script to compare fresh `create-app` versions of Grails/Grace so you can see what changed.


Just compare across tags:

* https://github.com/rainboyan/grace-versions/compare/v7.0.0...v7.0.7
* https://github.com/rainboyan/grace-versions/compare/v7.0.1...v7.0.7
* https://github.com/rainboyan/grace-versions/compare/v7.0.2...v7.0.7
* https://github.com/rainboyan/grace-versions/compare/v7.0.3...v7.0.7
* https://github.com/rainboyan/grace-versions/compare/v7.0.4...v7.0.7
* https://github.com/rainboyan/grace-versions/compare/v7.0.5...v7.0.7
* https://github.com/rainboyan/grace-versions/compare/v7.0.6...v7.0.7
* https://github.com/rainboyan/grace-versions/compare/v7.0.7...v7.0.8
* https://github.com/rainboyan/grace-versions/compare/v7.0.7...v7.0.9
* https://github.com/rainboyan/grace-versions/compare/v7.0.7...v7.0.10

From the git cli:

```
git diff v7.0.0..v7.0.7
git diff v7.0.1..v7.0.7
git diff v7.0.2..v7.0.7
git diff v7.0.3..v7.0.7
git diff v7.0.4..v7.0.7
git diff v7.0.5..v7.0.7
git diff v7.0.6..v7.0.7
git diff v7.0.7..v7.0.8
git diff v7.0.7..v7.0.9
git diff v7.0.7..v7.0.10
```
