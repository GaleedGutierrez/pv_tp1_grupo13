# What type of PR is this?

Check all applicable.

- [ ] 🍕 Feature
- [ ] 🐛 Bug
- [ ] 📝 Documentation Update
- [ ] 🎨 Style
- [ ] 🧑‍💻 Code Refactor
- [ ] 🔥 Performance Improvements
- [ ] 🧪 Test
- [ ] 🏗️ Build
- [ ] 👷‍♂️ CI
- [ ] 📦 Chore (Release)
- [ ] ⏪️ Revert

## Context

Gives the reviewer some context about the work and why this change is being
made, the WHY you are doing this. This field goes more into the product
perspective.

## Description

Provide a detailed description of how exactly this task will be accomplished.
This can be something technical. What specific steps will be taken to achieve
the goal? This should include details on service integration, job logic,
implementation, etc.

## Changes in the codebase

This is where becomes technical. Here is where you can be more focused on the
engineering side of your solution. Include information about the functionality
they are adding or modifying, as well as any refactoring or improvement of
existing code.

## Changes outside the codebase

If you have made changes to external services, need to add additional values to
the job settings, or need to add something new to the database, explain it
here. This may include updates to third-party services, changes to
infrastructure configuration, integration with external APIs, etc.

## Additional information

Provide any additional information that might be useful to the reviewer in
evaluating this pull request. This could include performance considerations,
design choices, etc.

## Related Tickets & Documents

For pull requests that relate or close an issue, please include them below. We
like to follow:

[Github's guidance on linking issues to pull requests](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue). <!-- markdownlint-disable-line MD013 -->

For example having the text: "closes #1234" would connect the current pull
request to issue 1234. And when we merge the pull request, GitHub will
automatically close the issue.

- Related Issue #
- Closes #

## QA Instructions, Screenshots, Recordings

_Please replace this line with instructions on how to test your changes, a note
on the devices and browsers this has been tested on, as well as any relevant
images for UI changes._

### UI accessibility checklist

_If your PR includes UI changes, please utilize this checklist:_

- [ ] 🧩 Semantic HTML implemented?
- [ ] ⌨️ Keyboard operability supported?
- [ ] 🛠️ Checked with [axe DevTools](https://www.deque.com/axe/) and addressed
- [ ] ⚠️ `Critical` and `Serious` issues?
- [ ] 🎨 Color contrast tested?

_For more info, check out the
[Forem
Accessibility Docs](https://developers.forem.com/frontend/accessibility)._

## Added Test?

- [ ] 👍 Yes.
- [ ] 🙅‍♂️ No, and this is why: _please replace this line with details on why
      tests have not been included_.
- [ ] 🙋 No, I need help with writing test.

## Added to documentation?

- [ ] 📜 README.md
- [ ] 📓 docs.opensouced.pizza
- [ ] 📕 storybook
- [ ] 🙅‍♂️ No documentation needed

## (optional) Are there any post deployment tasks we need to perform?

## (optional) What GIF best describes this PR or how it makes you feel?

![alt_text](gif_link)
