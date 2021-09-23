# theme-cleanup-workflow
Workflow to delete files and create a clean branch for Shopify theme integration

The workflow currently only remove the `node_modules` file. If you want to delete more files, you can call the rm action multiple times.

Actions used:
- [actions/checkout](https://github.com/marketplace/actions/checkout)
- [JesseTG/rm](https://github.com/marketplace/actions/remove-file)
- [dfm/force-push-branch-action](https://github.com/marketplace/actions/force-push-branch)
