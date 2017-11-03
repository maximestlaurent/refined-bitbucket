# 3.0.0 (2017-11-03)

After a long time of active development being dormant on this project, we are coming back with what I consider some great new features and improvements. Because of this, we are bumping to a new major release, v3.0.0! Check out the updated README to see some screenshots and gifs

The development environment for the extension was greatly improved as well, with changes that will make adding and testing new features a lot easier. We are hoping that future releases can come by quicker from now on.

If you stumble upon any weird behavior or bugs, please report an issue, I'll be be more than happy to tackle them as soon as I can. If you can have any quick question, you can hit me up on Twitter [@reyronald](http://www.twitter.com/reyronald).

### Features

* **Collapse-Diff**: Added button to collapse diffs in the Pull Request view. [Pull request 60](https://github.com/refined-bitbucket/refined-bitbucket/pull/60) and [pull request 67](https://github.com/refined-bitbucket/refined-bitbucket/pull/67).
* **Autocollapse**: Add file patterns in the Options page that you would like the extension to collapse automatically when the Pull Request. [Pull request 68](https://github.com/refined-bitbucket/refined-bitbucket/pull/68).
* **Pullrequest-ignore**: Add diff filename patterns in the Options page that you would like the extension to completely remove automatically when the Pull Request loads. [Pull request 70](https://github.com/refined-bitbucket/refined-bitbucket/pull/70).
* **Load-all-diffs**: Add button to load all failed diffs in Pull Request view. [Pull request 71](https://github.com/refined-bitbucket/refined-bitbucket/pull/71).

### Improvements

* **Merge-approvals**: Merge approvals feature removed. No longer necessary since it is [now implemented natively by Bitbucket with "merge checks"](https://confluence.atlassian.com/bitbucketserver/checks-for-merging-pull-requests-776640039.html), closes [issue 51](https://github.com/refined-bitbucket/refined-bitbucket/issues/51) and [issue 32](https://github.com/refined-bitbucket/refined-bitbucket/issues/32), [pull request 61](https://github.com/refined-bitbucket/refined-bitbucket/pull/61).
* **Occurrence-Highlighter**: Now when double-clicking whitespace/indentation in diffs, no highlighting occurs, closes [issue 59](https://github.com/refined-bitbucket/refined-bitbucket/issues/59), [pull request 62](https://github.com/refined-bitbucket/refined-bitbucket/pull/62)
* **Development**: _browserify_ build and and _tape_ test suite were replaced with _webpack_ & _babel_ and _ava_. Since now we are using _babel_ transpilation, the latest features of ES that it supports can be used. Also a _watch_ mode is available! [Pull request 65](https://github.com/refined-bitbucket/refined-bitbucket/pull/65).

### Bug fixes

* **Occurrence-Highlighter**: Double-clicking an already highlighted word doesn't remove it, closes [issue 64](https://github.com/refined-bitbucket/refined-bitbucket/issues/64), [pull request 69](https://github.com/refined-bitbucket/refined-bitbucket/pull/69).

# 2.6.4 (2017-10-16)

### Bug fixes

* **Occurrence-Highlighter**: When double-clicking a word that exists multiple times in the same HTML node, the selection remains in the clicked word, closes [issue #57](https://github.com/refined-bitbucket/refined-bitbucket/issues/57), [pull request 58](https://github.com/refined-bitbucket/refined-bitbucket/pull/58).

# 2.6.3 (2017-10-15)

### Bug fixes

* **Occurrence-Highlighter**: Now the selection is maintained when highlighting word occurrences when creating comments and tasks, closes [issue #55](https://github.com/refined-bitbucket/refined-bitbucket/issues/55), [pull request 56](https://github.com/refined-bitbucket/refined-bitbucket/pull/56).


# 2.6.2 (2017-10-12)

### Bug fixes

* **Occurrence-Highlighter**: Now the selection is maintained when highlighting word occurrences inside comments and tasks, closes [issue #52](https://github.com/refined-bitbucket/refined-bitbucket/issues/52), [pull request 53](https://github.com/refined-bitbucket/refined-bitbucket/pull/53).

# 2.6.1 (2017-09-27)

### Bug fixes

* **Occurrence-Highlighter**: Now the selection is maintained when highlighting word occurrences, closes [issue #38](https://github.com/refined-bitbucket/refined-bitbucket/issues/38), [pull request 50](https://github.com/refined-bitbucket/refined-bitbucket/pull/50).

### Language support

* Added C++ language support for files with extension `.cc`
* Added JSX language support for VueJS files with extension `.vue`
* Added Kotlin language support for files with extension `.kt`

# 2.5.1 (2017-07-19)

No changelog until this version.