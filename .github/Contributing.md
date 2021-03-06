# Welcome 

Welcome to the UK Sector File repository, for everything sector related in the UK!  Thank you for your interest in contributing to the project.  Full details and guidelines on how to ensure this project is managed well are included below.

# Contributor license agreement
By submitting code as an individual you agree that VATSIM UK can use your ammendments, fixes, patches, changes, modifications, submissions and creations in the production of the UK Sector File and that the ownership of your submissions transfers to VATSIM UK in their entirety.

# Helping others
Please help other UK Sector File users wherever you can (everybody starts somewhere).  If you require assistance (or wish to provide additional assistance) you can find our contributors in the VATSIM UK slack team.

To access Slack, you can visit https://core.vatsim-uk.co.uk and follow the registration instructions.  Once you've logged in, find the channel "UKSectorFile"

# I want to contribute!

If you wish to contribute to the UK Sector File project, there's many ways in which you can help out.

## Contributing to the data

If you're just getting started with GitHub (and project contributions) then we suggest you take a look at issues marked with the "up-for-grabs" label.  These issues will be of resonable size and challenge, for anyone to start contributing to the project.  [This was inspired by an article by Ken C. Dodds](https://medium.com/@kentcdodds/first-timers-only-78281ea47455#.wior7p101).

If you're comfortable with contributing to Open Source projects on GitHub please ensure you read our expectations for issue tracking, feature proposals and merge requests.

**Please avoid** adding airac related commits until you've seen an issue created for them - anything else is fair game.

## Testing the sector file

At present there isn't a publicly accessible auto-generation tool for the data within the repository.  We're working hard to make our current tool stable enough to release into the public domain so that open source contributions can be made to that, too, and others can use (and test) the latest development version.

## Issue Tracking

If you require **support** with the Sector File or Euroscope, please utilise our Slack channels for this purpose.  Issues regarding the features and functions of Euroscope or how to load the Sector File will not be handled.  The issue tracker is for feature requests and bugs concerning the UK Sector File itself.

When submitting an issue, there's a few guidelines we'd ask you to respect to make it easier to manage (and for others to understand):
* **Search the issue tracker** before you submit your issue - it may already be present.
* When opening an issue, a template is provided for you.  Please provide as much information as requested to ensure others are able to act upon the requests or bug report.
* **Issue Weight** allows us to get an idea of how much work is required.  If it's a simple change (such as modification of runway identifiers) then the weight will likely be quite low (1 or 2).  Tasks that are unlikely to involve huge changes (such as amending an SMR or adding some extra stands) might be around a 4 or 5.  Issues that involve changes of sector lines/ownership (for example, incorporating a whole new sector) will be an 8 or 9.
 * If something is very large (i.e. an 8 or 9) it should be split up into smaller tasks that can be managed separately by different people.
* If you disagree with the weight of an issue, comment and discuss this with the developers to reach a suitable medium (other contributors may base their decision to contribute on the weight assigned)
* Please ensure you add screenshots or documentation references for bugs/changes so we can quickly ascertain if the request is suitable.

## Merge Requests

We welcome merge requests with fixes and improvements to the Sector File project.  The features we really would like public support on are marked with "up-for-grabs" but other improvements are also welcome - please ensure you read over the merge work-flow below.

If you wish to add a new feature or you spot a bug that you wish to fix, **please open an issue for it first** on the [UK Sector File issue tracker](https://gitlab.com/vatsim-uk/UK-Sector-File/issues).

The work-flow for submitting a new merge request is designed to be simple, but also ensure consistency from **all** contributors:
* Fork the project into your personal space on GitLab.com
* Create a new branch (with the name issue-<issue_number>, replacing issue_number with the issue number you're resolving)
* Commit your changes
 * When writing commit messages, consider closing your issues via the commit message (by including "fix #22" or "fixes #22", for example ).
  * The issues will be referenced in the first instance and then closed once the MR is accepted.
* **Add your changes to the CHANGELOG.md file** - this can be found in [UK-Sector-File/.github/CHANGELOG.md](https://github.com/VATSIM-UK/UK-Sector-File/blob/master/.github/CHANGELOG.md)
* Push the commit(s) to your fork
* Submit a merge request (MR) to the master branch
* The MR title should describe the change that has been made
* The MR description should confirm what changes have been made, how you know they're correct (with references)
 * Please include any relevant screenshots to prove the changes work - this is particu
* Ensure you link any relevant issues in the merge request (you can type hash and the issue ID, eg #275).  Comment on those issues linking back to the MR (you can reference MRs using the format !<MR_ID> for example !22).
* Be prepared to answer any questions about your MR when it is reviewed for acceptance

**If you are actively working on a large change** consider creating the MR early but prefixing it with [WIP] as this will prevent it from being accepted *but* let other people know you're working on that issue.

**Please** keep your changes in a single MR as small as possible (relating to one issue) as this makes it easier to review and accept.  Large MRs with a small error will prevent the entire MR being accepted (and could potentially miss the airac/sector release date).

# Expectations
As contributors and maintainers of this project, we pledge to respect all people who contribute through reporting issues, posting feature requests, updating documentation, submitting merge requests or patches, and other activities.

We are committed to making participation in this project a harassment-free experience for everyone, regardless of level of experience, gender, gender identity and expression, sexual orientation, disability, personal appearance, body size, race, ethnicity, age, religion, or favourite aircraft.

Project maintainers have the right and responsibility to remove, edit, or reject comments, commits, code, issues and other contributions that are not aligned to this Code of Conduct.

This Code of Conduct applies both within this project space and public spaces when an individual is representing the project or its community.
