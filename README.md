# Welcome Students of 4156

Please follow the assignment specifications on Courseworks when completing this project.

## Using PMD as the static bug finder
I used the QuickStart guide on https://pmd.github.io/

```
// Where I downloaded the source file
$ pwd
  COMS 4156 Advanced SE/Projects/4156-Miniproject-2024-Students-Java/IndividualProject
$ wget https://github.com/pmd/pmd/releases/download/pmd_releases%2F7.5.0/pmd-dist-7.5.0-bin.zip
$ unzip pmd-dist-7.5.0-bin.zip
$ alias pmd="$HOME/pmd-bin-7.5.0/bin/pmd"
$ pmd check -d src/main/java/dev/coms4156/project/individualproject -R rulesets/java/quickstart.xml -f text
```
This command also works find with my project.

```
$ mvn pmd:check
```
