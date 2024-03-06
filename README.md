# Workspace cleanup action

A simple GitHub Action to clean up your workspace.

The action will delete all files and folders in the workspace, including the files starting with a dot.

The action will check that the workspace is not the root of the filesystem before deleting anything.

## Usage

The action can be used in a workflow like this:
```yaml
steps:
  - uses: kuznetsss/workspace-cleanup@v1
```
