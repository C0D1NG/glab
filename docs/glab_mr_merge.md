## glab mr merge

Merge/Accept merge requests

### Synopsis

Merge/Accept merge requests

```
glab mr merge <id> [flags]
```

### Options

```
  -h, --help                     help for merge
  -m, --message string           Get only closed merge requests
  -d, --remove-source-branch     Remove source branch on merge
      --sha string               Merge Commit sha
  -s, --squash                   Squash commits on merge
      --squash-message string    Squash commit message
      --when-pipeline-succeeds   Merge only when pipeline succeeds. Default to true (default true)
```

### Options inherited from parent commands

```
  -R, --repo string   Select another repository using the OWNER/REPO format or the project ID. Supports group namespaces
```

### SEE ALSO

* [glab mr](glab_mr.md)	 - Create, view and manage merge requests

###### Auto generated by spf13/cobra on 14-Aug-2020