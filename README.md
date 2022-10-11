# fabric-project-template
A template repository organized for projects using the FABRIC Testbed

# To-do:
- [ ] Choose a license:
  - [Instructions](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository)
  - Click [here](./LICENSE) to edit the license file if you would like to choose a license other than MIT: "(c) 2022 FABRIC at Clemson".
- [ ] Edit CODEOWNERS
  - [Instructions](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners)
  - *"Code owners are automatically requested for review when someone opens a pull request that modifies code that they own."*
  - Click [here](./CODEOWNERS) to edit the CODEOWNERS file. Copy and paste the following text to setup CODEOWNERS to set up defaults in our Organization:

```
# These owners will be the default owners for everything in
# the repo. Unless a later match takes precedence,
# @bformby @bjrice13 @silvertenor and @SriChandana98 will be
# requested for review when someone opens a pull request.
*       @bformby @bjrice13 @silvertenor @SriChandana98

### See a full example at https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners
```

- [ ] Set up branch protections for the main branch
  - [Instructions](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/about-protected-branches), specifically [these](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/managing-a-branch-protection-rule)
  1. Go to the repository's settings and click on "Branches" (https://github.com/fabric-at-clemson/YOUR_PROJECT/settings/branches).
  2. Click on the <kbd>Add rule</kbd> button next to "Branch protection rules".
  3. Type in `main` for the "Branch name pattern".
  4. Check the following checkboxes:
  - [x] **Require a pull request before merging**
    - [x] **Require review from Code Owners** (if using CODEOWNERS)
  - [x] **Do not allow bypassing the above settings** (will prevent admins from pushing directly to main without a pull request)
  5. Click the green <kbd>Create</kbd> button at the bottom of the page.
- [ ] Remember to check out branches; don't edit on the main branch!
- [ ] Add your files to this repository. Use pull requests to merge into main.
- [ ] Edit/change this page to be your README.
- [ ] Create versions using Releases.
- [ ] [Use Zenodo to create a DOI for citing your code in research.](https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content)
