Guidelines {#code_guidelines}
================================

This documentation is aimed at developers actively contributing to Pencil. Please follow the below guidelines when making contributions. Please feel free to add extra sections as you see fit to improve our development process.

## Pull Request Guidelines

Our Pull Request Guidelines are based off of the [Creative Commons guidelines](https://opensource.creativecommons.org/contributing-code/pr-guidelines/).

These guidelines should be followed throughout your development process. Not just once you have made your change.

1. Make a branch
    -  Create a branch for each seperate issue that you are working on. Do not make changes to the default branch. This will allow you to keep changes isolated and develop without interference until your change is ready.

2. Push your code ASAP (even before it is fully ready)
    - Push code as soon as you have a minimal product put together. Make the pull request and mark the title with "[WIP]". You can specify these as [draft pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests#draft-pull-requests). The request will not be able to be merged and the owners will not be prompted to review until you mark ready for review.
    - For more information on creating a pull request see the following [documentation](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request).
    - Make changes to your Pull Request as information becomes available during development.

3. Describe your pull request
    - Use the template specified below labeled "Pull Request Template". Fill out each section for the ideal amount of information for reviewers. Too much detail about your change is better than too little.
    - Put extra emphasis in describing how you tested your change. This is critial to the reviewer on making a decision to merge your pull request. Adding in unit tests is almost always a good idea and in some cases required to merge your pull request. For non-code changes like markdown use the preview tab to ensure changes follow the general aesthetic of the rest of the repository.

4. Request Review
    - If you created a draft pull request mark ready for review and remove WIP from the title. Otherwise create a pull request by using the above documentation.
    - Request a review from the project mmaintainer.

5. Incorporate Feedback
    - If the reviewer marks 'Changes Requested', you need to review the comments and address the concerns. To update your PR push to the same branch. You do not need to close the PR and open a new one.
    - Re-request review.
    - Make a comment asking the reviewer to please take another look (PTAL).


## Pull Request Template

This request template is from [Embedded Artistry by Phillip Johnston](https://embeddedartistry.com/blog/2017/08/04/a-github-pull-request-template-for-your-projects/).

### Description

Please include a summary of the change and which issue is fixed. Please also include relevant motivation and context. List any dependencies that are required for this change.

Fixes # (issue)

### Type of change

Please delete options that are not relevant.

- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] This change requires a documentation update

### How Has This Been Tested?

Please describe the tests that you ran to verify your changes. Provide instructions so we can reproduce. Please also list any relevant details for your test configuration

- [ ] Test A
- [ ] Test B

**Test Configuration**:
* Firmware version:
* Hardware:
* Toolchain:
* SDK:

### Checklist:

- [ ] My code follows the style guidelines of this project
- [ ] I have performed a self-review of my own code
- [ ] I have commented my code, particularly in hard-to-understand areas
- [ ] I have made corresponding changes to the documentation
- [ ] My changes generate no new warnings
- [ ] I have added tests that prove my fix is effective or that my feature works
- [ ] New and existing unit tests pass locally with my changes
- [ ] Any dependent changes have been merged and published in downstream modules