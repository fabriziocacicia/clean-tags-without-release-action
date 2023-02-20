# Delete Tags without Release Action
A Github Action that delete all the tags of a repository that are not associated to a Release

## Usage
Add the following step to your workflow:

```yaml
- uses: fabriziocacicia/delete-tags-without-release-action@v0.1.0
  env:
    GITHUB_TOKEN: ${{ secrets.PERSONAL_ACCESS_TOKEN }}
```

