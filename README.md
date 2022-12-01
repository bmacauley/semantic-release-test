# semantic-release-test
Explore the use of semantic-release for auto release tagging within a  github actions CI pipeline

## Features
- github flow branch strategy (ie short lived feature branch)
- auto-create PR when a new branch is created
- squash merge to main on completed PR
- use semantic-release to automatically create correct semver release tags(ie major.minor.fix) and to update the changelog


# semantic-release config





## tools/github actions used
- [github cli](https://cli.github.com/)
- [semantic-release](https://semantic-release.gitbook.io/semantic-release/)
- [semantic-release/changelog](https://github.com/semantic-release/changelog)
- [semantic-release/github](https://github.com/semantic-release/github)
- [semantic-release/gitlab](https://github.com/semantic-release/gitlab)
- [amannn/action-semantic-pull-request](https://github.com/amannn/action-semantic-pull-request)
- [Semantic PRs app](https://github.com/Ezard/semantic-prs)



# test scenarios



## Reference
- [semver](https://semver.org/)
- [semantic-release](https://github.com/semantic-release/semantic-release)
- [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/)
- [conventional changelog](https://github.com/conventional-changelog)
- [commitlint](https://github.com/conventional-changelog/commitlint)
- [semantic release and changelog tools](https://www.nextrelease.io/kb/why-should-i-use-next-release/)
- [https://keepachangelog.com/en/1.0.0/](https://keepachangelog.com/en/1.0.0/)
- [angular commit message conventions ](https://github.com/angular/angular/blob/main/CONTRIBUTING.md)
- [introduction to semantic versioning](https://www.geeksforgeeks.org/introduction-semantic-versioning/)
- [branching & releasing strategy that meets github flow](https://medium.com/hackernoon/a-branching-and-releasing-strategy-that-fits-github-flow-be1b6c48eca2)



## Authors
* [Brian Macauley](https://github.com/bmacauley) (<brian.macauley@gnail.com>)

## License
[MIT](/LICENSE)