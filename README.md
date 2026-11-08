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

* https://github.com/rainboyan/grace-versions/compare/v5.3.0...v5.3.6
* https://github.com/rainboyan/grace-versions/compare/v5.3.1...v5.3.6
* https://github.com/rainboyan/grace-versions/compare/v5.3.2...v5.3.6
* https://github.com/rainboyan/grace-versions/compare/v5.3.3...v5.3.6
* https://github.com/rainboyan/grace-versions/compare/v5.3.4...v5.3.6
* https://github.com/rainboyan/grace-versions/compare/v5.3.5...v5.3.6
* https://github.com/rainboyan/grace-versions/compare/v5.3.6...v6.0.0

From the git cli:

```
git diff v5.3.0..v5.3.6
git diff v5.3.1..v5.3.6
git diff v5.3.2..v5.3.6
git diff v5.3.3..v5.3.6
git diff v5.3.4..v5.3.6
git diff v5.3.5..v5.3.6
git diff v5.3.6..v6.0.0
```
