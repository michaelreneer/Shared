## Shared

#### Install Shared Submodule

Add Shared as a [submodule][] in git.

```bash
cd "<Project Directory>"
git submodule add "git@github.com:michaelreneer/Shared.git"
```

Open Xcode and drag the Shared folder from Finder into the Project Navigator.

Commit the changes.

```bash
git commit -am "Added Shared to project."
```

## License

Copyright (c) 2016 Michael Reneer. See LICENSE for details.

[submodule]: http://git-scm.com/book/en/Git-Tools-Submodules "Submodule"
