Self-learning of git and github
============
For some basic git and github instructions to manage a project (e.g. Python).

Get started
------------

### Useful resources
- [git book](https://git-scm.com/book/en/v2)
- [git for r](https://intro2r.com/github_r.html)
- [git for vs code](https://code.visualstudio.com/docs/sourcecontrol/overview)
- [.gitconfig template](https://gist.github.com/cxiao13/f3504988d2b01cd8065adc49fdfb15bb)
    - tips setting vs code as default: `core.editor = code --wait` ```[diff]
                                                                    tool = default-difftool
                                                                    [difftool "default-difftool"]
                                                                    cmd = code --wait --diff $LOCAL $REMOTE```



Project Organization
-------------
📦git_learn
 ┣ 📂data
 ┃ ┣ 📂interm
 ┃ ┣ 📂processed
 ┃ ┗ 📂raw
 ┣ 📂git-learn-project
 ┃ ┣ 📂data
 ┃ ┣ 📂features
 ┃ ┣ 📂models
 ┃ ┗ 📂visualization
 ┣ 📂guide
 ┣ 📂models
 ┣ 📂notebooks
 ┣ 📂references
 ┣ 📂reports
 ┃ ┗ 📂figures
 ┣ 📜README.md
 ┗ 📜requirements.txt