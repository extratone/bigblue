# [GitWord](https://github.com/vigente/gerardus/wiki/Integrate-git-diffs-with-word-docx-files)

Now you can see a pretty coloured diff with the changes you have made to your .docx file since the last commit:

```
git wdiff bigblue.docx
```

To see all changes over time:

```
git log -p --word-diff=color bigblue.docx
```

