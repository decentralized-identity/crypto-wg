# New work Item Process

The content below outlines the process under which a new working group item is
established and the ongoing expectations of work item owners.

## Creating a new work item

1. Ensure that you have completed the DIF IPR process. You must have at least
   two co-owners from different organizations for your work item to be
   considered.
2. Fork this repository to your GitHub account and clone the fork to your local
   machine.
3. In the project directory on your local machine, copy
   `templates/work_item.md` into lowercase snakecase "short name" for your work
   item in `work_items/`. For example, `cp templates/work_item.md
   work_items/credential_revocation.md`. Add your work item to the list of
   active work items in `work_items/README.md`.
4. Populate your work item by completing all the sections in the template,
   including answering all the questions.
5. Commit your changes locally and push to your GitHub account's fork of this
   repository.
6. Create a Pull Request against the parent repository including your local
   changes. The proposed work item will then be discussed at the next available
   WG meeting where adopting the work item will be voted upon. Your item
   co-owners **must** express in the Pull Request via GitHub comment that they
   accept the responsbilities of work item ownership.
7. Upon approval via merging, begin an email thread with the chairs or discuss
   asynchronously if you require any administrative resources from DIF, such as
   a regularly scheduled Zoom meeting link, inclusion on the
   [DIF calendar](mailto:decentralized.identity@gmail.com), a location
   to store notes and recordings, or any other help facilitating your work
   item.

## Work item ownership responsibilities

As a work item owner, you will have the following responsibilities:
- Timely response to questions and status check-ins about the work item by the
  chairs and other DIF members.
- Commitment to designating and sending a work item representative for all
  Applied Crypto WG bi-weekly meetings who can speak on the status of the work
  item and summary of events
- Commitment to timelines and scope of deliverables and/or meetings, and being
  proactive in communications to the chairs and the group upon any changes to
  these. Changes to the work item are made and approved in the same Pull
  Request process described above, except the PR should contain changes to the
  work item markdown file instead of adding a new one.
- If the work item is intended to become a standards proposal at an external
  standards organization, identify the key people in the external organization,
  establish and maintain a relationship with them and be proactive liaison
  between this working group and the external standards body.
