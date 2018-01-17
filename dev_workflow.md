# Lexicata Development Guidelines

## Branch Naming

<table>
  <thead>
    <tr>
      <th>Instance</th>
      <th>Branch</th>
      <th>Description, Instructions, Notes</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Stable</td>
      <td>stable</td>
      <td>Accepts merges from Working and Hotfixes</td>
    </tr>
    <tr>
      <td>Working</td>
      <td>master</td>
      <td>Accepts merges from Features/Issues and Hotfixes</td>
    </tr>
    <tr>
      <td>Features/Issues</td>
      <td>topic-\*</td>
      <td>Always branch off HEAD of Working</td>
    </tr>
    <tr>
      <td>Hotfix</td>
      <td>hotfix-\*</td>
      <td>Always branch off Stable</td>
    </tr>
  </tbody>
</table>

##### Naming Branches for Features and Bugs
* Must branch from: master
* Must merge back into: master
* Branch naming convention: feature-<issue number> or bug-<issue number>

Source: [Branching](https://gist.github.com/digitaljhelms/4287848)

## Git Commit Format

Git commit messages should include a title, of no more than 50 characters, describing the completed work. Omit a period or other ending punctuation from the title.

The body of the message should include details about what was changed and why, in paragraph form. It is not necessary to detail how the change was made as the code itself can answer that question. When possible, reference the issue number in the commit when closing the issue.

For more detailed information on how to structure your commit message, see the following resources:

* [Chris Beams on git commits](https://chris.beams.io/posts/git-commit/)
* [Jira - using smart commits](https://confluence.atlassian.com/fisheye/using-smart-commits-298976812.html)

## Pull Requests

There should be one PR per story and one story per PR. Pull Requests should be code reviewed before closing and merging to the master branch. When possible, commits in a PR should be squashed before merging.

When submitting a PR, tag/assign the person who should be completing the code review.

All code submitted for a PR must be tested. If tests are not included, the submitter of the PR should includes notes detailing why it was not possible or reasonable to write tests.

## Code Review

### Who
Applicable Team for story completes review using GitHub's PR review tools. Code Review can move to a verbal discussion if needed.

### When
Reviewer of the PR should complete the review the morning following the submission of the PR so that no PR remains unreviewed longer than 24 hours or 1 business day.

## QA

### Who
The Product Owner typically acts as the QA reviewer as he is the one who can approve that the business requirement has been met.

### How
Reviewers should review stories in the QA column on Jira to verify completion. Once completed, the reviewer should move the story to "Done". If a story needs revisions, the reviewer should include detailed notes in the comments regarding the revisions to be made. The story will then start over in the To Do column.

If a bug is found, the reviewer should include the following:
* A description of the issue
* Steps to reproduce the issue
* The URL and a screenshot of the problem area or error message.

### When
Review stories for completion on a rolling basis. The reviewer should QA any story in the QA column within 1 business day to ensure all stories are completed in time for the sprint's release. Any stories that have not successfully passed QA by the end of the sprint will roll in to the next release.

## Deployment

Sprints are released/deployed on the last day of the sprint. Items that have not passed QA will not be released at the end of the sprint and will roll in to the next release.
