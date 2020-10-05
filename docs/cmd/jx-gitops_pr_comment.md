## jx-gitops pr comment

Add comment to the pull request

### Usage

```
jx-gitops pr comment
```

### Synopsis

Adds a comment to the current pull request

### Examples

  # add comment
  jx-gitops pr comment "Message from Jenkins"

### Options

```
      --comment string      comment to add
      --dir string          the directory to search for the .git to discover the git source URL (default ".")
      --git-kind string     the kind of git server to connect to
      --git-server string   the git server URL to create the git provider client. If not specified its defaulted from the current source URL
      --git-token string    the git token used to operate on the git repository
  -h, --help                help for comment
      --pr int              the Pull Request number. If not specified we detect it via $PULL_NUMBER or $BRANCH_NAME environment variables
  -r, --repo string         the full git repository name of the form 'owner/name'
```

### SEE ALSO

* [jx-gitops pr](jx-gitops_pr.md)	 - Commands for working with Pull Requests

###### Auto generated by spf13/cobra on 3-Oct-2020