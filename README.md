# EducationUI

UI generation for education. Content included as submodules.

```
git submodule add https://github.com/DataONEorg/BestPractices.git bestpractices
git submodule add https://github.com/DataONEorg/Education.git lessons
```

When cloning:

```
git clone --recursive https://github.com/DataONEorg/EducationUI.git
```

It is important to note that `/ui/bestpractices` and `/ui/lessons` are both
separate git repositories. Git commands should not attempt to perform actions
across repositories, e.g. attempting to `git mv` between repositories won't
work.
