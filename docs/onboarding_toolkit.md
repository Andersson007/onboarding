# Ansible project onboarding

Welcome to the Ansible ecosystem of projects! This document guides you 
through the steps to take to become part of the Ansible ecosystem.

# Why be part of the Ansible ecosystem
Being a part of the Ansible ecosystem means you are tapping into a large and
thriving community of passionate people working and volunteering in Ansible.

The major benefits of becoming part of the Ansible ecosystem include:

* A presence on docs.ansible.com/ecosystem for your project documentation,
 as well as being part of the official Ansible ReadTheDocs space.
* A presence on the (future) Ansible.com to introduce your project.
* Dedicated communications channels (chat and forum) to communicate with your
community and attract other community members to your project.

# Getting started

The first step in becoming part of the Ansible ecosystem is to engage with the 
[Ansible community team](https://docs.ansible.com/ansible/latest/community/communication.html)
to discuss your options and how your project fits into the Ansible community. 
The remaining sections here assume that discussion is complete and the community team approves 
your project for the Ansible community of projects.

# Setting up your GitHub repository

The Ansible ecosystem projects exist in the following two GitHub organizations:

* [ansible](https://github.com/ansible) - Access is controlled by Red Hat
* [ansible-community](https://github.com/ansible-community) - Access is controlled by the community, 
under Red Hat sponsorship

**NOTE:**
This toolkit does not apply to Ansible collections in the [ansible-collections](https://github.com/ansible-collections/overview) organization.
See the [Collection contributor guide](https://docs.ansible.com/ansible/latest/community/contributions_collections.html)
for details.

We recommend most Ansible projects use the ansible-community GitHub organization.

## Transferring existing repositories

Repository transfers are available if your project already exists somewhere else in GitHub.
Contact the [Ansible community team](https://docs.ansible.com/ansible/latest/community/communication.html)
for assistance. Transferred projects must follow the same format as described in this guide.

## Creating new projects

For new projects, use the [project-template](https://github.com/ansible-community/project-template) to 
create a project with the default files.

## Submitting your project for inclusion

* Open up issues and PRs for task tracking and community contributions.
* [Disable the GitHub discussions](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/enabling-features-for-your-repository/enabling-or-disabling-github-discussions-for-a-repository).
Use the [Ansible Community forum](https://forum.ansible.com/) for community
and project discussions.
* [Disable the repository wiki](https://docs.github.com/en/communities/documenting-your-project-with-wikis/disabling-wikis) 
for project documentation. See the sections below on documentation and using the Ansible forum.

## Common files

**NOTE:** If you use the Ansible GitHub project template, these files are included
in the created repository.

All Ansible ecosystem projects MUST include the following files listed in
the [project_template repository's README](https://github.com/ansible-community/project-template#template-structure).

## Optional other steps

While not required, you should consider adding the following to your project repository:

  * Provide Issue and PR templates to improve the contributor experience.

# Creating your community space

Each Ansible ecosystem project should use the Forum and an associated tag
to communicate and collaborate with the community. For more information, see:

- [Ansible Communication guide](https://docs.ansible.com/ansible/devel/community/communication.html#forum)
- [Ansible Forum video demos](https://forum.ansible.com/t/discourse-video-demos/102)
- [Forum tips](https://forum.ansible.com/tag/forum-tips)
- [Communication section](https://github.com/ansible-community/project-template#communication) in the project_template repository's README.md file

Reach out to the [community team](https://forum.ansible.com/g/CommunityTeam) to request new tag(s) for your project in the forum.

## Working Groups

Not every project requires a working group. We advise projects to use
the Ansible forum and GitHub issues as much as possible
to be accessible to all timezones. 

A working group is your group of contributors, along with ways to coordinate
your work. This includes a tag or group for the forum and optionally a matrix room. 
 
Synchronous project meetings are an option and you can use the 
[Forum Events calendar](https://forum.ansible.com/c/events/8) to announce your meetings. 
Be aware that any real-time meetings will tend to exclude contributors not in or around the 
meeting timezone.

See the [Working group community guidelines](https://docs.ansible.com/ansible/latest/community/communication.html#working-groups)
for complete details on setting up and running a working group, including synchronous meetings
on Matrix and ansynchronous discussions on the forum.

## Raise awareness about your project

Use the following communication options to let people know about your Ansible project:

 * Announce your project to [The Bullhorn](https://forum.ansible.com/c/news/bullhorn/17).
 * Ask [the community team](https://docs.ansible.com/ansible/latest/community/communication.html)
  to announce your project in Mastodon.
 * Join the [community WG meeting](https://matrix.to/#/#community:ansible.com)
 to announce your new project.

# Nurture and grow your community

* Use the communications options listed to keep people up to date on 
your community and project accomplishments. 
This includes Matrix, Bullhorn, and forum updates for:

    * New releases or changes
    * Requesting help
    * Kudos for community contributors
    * Any other ideas/accomplishments/calls for help for your project.

* Work in the community...decide in the community - The more your project 
team can engage in the open, the stronger your community will be. This includes
discussing issues, features, and in general, working as a team by default, 
in your matrix and forum areas. If possible, you can empower the community 
to help develop project roadmaps, for example. 
* Ask for help! Some people may not realize you are looking for help in areas
 if you do not ask. And specific asks/issues work better than generic calls for help.

# Creating your documentation

We have a [Documentation guide](./docs_toolkit.md) to help you design 
and publish your documentation to ReadTheDocs as part of the Ansible ecosystem.

# Project governance

These are suggestions on how to govern your projects for an inclusive community.

* Give trusted contributors merge rights.
* Enable CI in your github repo to automate testing/validation where possible.
* Discourage PR owners from merging their own PRs. Each PR should have 
one or more approvals before merging.
* Have a project roadmap!
