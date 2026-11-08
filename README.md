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

* https://github.com/rainboyan/grace-versions/compare/v6.1.2...v6.2.2
* https://github.com/rainboyan/grace-versions/compare/v6.2.0...v6.2.2
* https://github.com/rainboyan/grace-versions/compare/v6.2.1...v6.2.2
* https://github.com/rainboyan/grace-versions/compare/v6.2.2...v6.2.3

From the git cli:

```
git diff v6.1.2..v6.2.2
git diff v6.2.0..v6.2.2
git diff v6.2.1..v6.2.2
git diff v6.2.2..v6.2.3
```
