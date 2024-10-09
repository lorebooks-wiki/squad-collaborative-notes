---
tags:
  - meta
---
The **Squad Leads** represent the team members in Recap Time Squad that forms the leadership team consisting of lead maintainers from different projects under the organization.

This wiki page is adopted from [ArchWiki's Project Leader](https://wiki.archlinux.org/title/DeveloperWiki:Project_Leader), licensed under [GNU FDL 1.3 or later](https://www.gnu.org/copyleft/fdl.html).

## Joining `@recaptime-dev/squad-leads`

### Qualifications

Being part of Recap Time Squad as a team member is not required, although if you're from the community you may be required to complete the onboarding process.

Required qualifications for applicants include:
- Valid contributions to the open-source community, either in code or non-code formats.
- No major incidents WITHIN 10 years involving breaking [the Community Code of Conduct](https://policies.recaptime.dev/code-of-conduct) or the Philippine/US federal laws, including communities outside Recap Time Squad.
	- If there are any major incidents but the moderation/legal intervention has since lapsed in the last 2 years since expiration before application, we will review your case alongside doing a extended background checks.

Requirements include:
- A non-disposable email address and at least one alternative contact method

Optional qualifications and requirements include, but they are not showstoppers for us:
- Proficiency and experience in using the Linux command line for frontend/backend/full-stack app development or system administration
- Experience in maintaining and/or leading an open-source project

## Roles of Squad Leads

### (SA)BDFL

> [!warning] This role in its current form is temporary.
> In the future, the title SABDFL will be renamed to Project Leader as we onboard additional team members and transitioning our governance model into a combination of mertiocracy and open community-based governance (in form of exit to community (E2C)).

The (SA)BDFL (expanded: (Self-Assigned) Benelovent Dictator for Life) is the person who administratively manage Recap Time Squad's resources and IP and the final decision maker (and sometimes tiebreaker) in the [RfC process](https://rfcs.recaptime.dev). Since its inception, ~[[ajhalili2006]] is the current SABDFL of Recap Time Squad, alongside his role as  an open-source developer.

Responsibilities of a SABDFL/project leader include:

- Being the legal representative and contact point/liasion between our fiscal host (currently HCB in the process of application, although it might change in the future) in terms of managing the organization's funds and resources as well as in legal matters.
- Managing and maintaining projects and services alongside other team members and the community within the organization.
- Making decisions that may affect both the organization, its projects and policies, including any legal matters.
- Serves as a tiebreaker in case of a tie in decision-making
- Serves as the final decision maker in organizational governance and its policies.

The term length for the project leader/SABDFL is currently set to unlimited unless they stepped down, died or triggered a emergency election involving leadership change.

### Infrastructure Sudoer

The Infrastructure Sudoer is a person that have administrative access to our GitHub/GitLab/sourcehut namespaces, cloud provider accounts (including Cloudflare and Google Cloud/Workspace) and Tailscale network (referred to as tailnet in the official Tailscale documentation), assisting the SABDFL in maintaining infrastructure health and doing IT admin tasks.

Responsibilities of infrastructure sudoers include:

- Handle most IT admin workloads in GitHub, GitLab, sourcehut, Google Workspace/Cloud Identity, Microsoft 365 and Tailscale.
- Manage Cloudflare resources under our accounts, including DNS records and domains registered under CloudFlare Registrar.
- Manage the access requests issue tracker and triage its tickets in a timely manner.