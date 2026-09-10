Project Proposal — CSCI-8420 Group 2

Team: Mujib Latifi · Kowshik Chowdhury · Leonard Meredith · Trung Phan · Hrudhay Rao Chepyala Repository: [link to this repo] Project Board: [link to GitHub Project] Date: [submission date]

1. Open-Source Software

Software: [name — pending Issue #1] Repository: [link to the software's open-source repo — pending Issue #1]

2. Systems Engineering View

(Issue #3)

Hypothetical operational environment: [home / office / enterprise / bank / government — describe the setting and why users there would deploy this software]

Systems engineering diagram:

[Embed diagram image here, e.g. ![systems diagram](diagrams/systems-view.png). Diagram should show the software's components, the actors/users involved, adjacent systems it interacts with, network zones, and trust boundaries within the chosen environment.]

3. Security Needs, Threats, and Features

(Issue #4)

Threats perceived by users

[List realistic threats a user in this environment would worry about — who the likely attacker is, what they're after, and the attack surface.]

Security features in the software

[List the software's actual security features that address the threats above.]

Threat → Feature mapping
Threat	Addressed by
[threat]	[feature]
[threat]	[feature]
4. Team Motivation

(Issue #5)

[Why the team chose this project — tie it to team skills/interests (networking background, Go learning goal, research interest) and to what's genuinely useful or interesting about the software itself.]

5. Open-Source Project Description

(Issue #6)

What it is: CrowdSec Is an Open-source preventative Fail2Ban service that instead of reacting to known malicious behavior and banning appropriately; leverages all that run the program to help stop known malicous IP's. For instance, if someone were to try and bruteforce your machine, fail2ban would detect the brute-force attempt and ban you from trying to access that machine. CrowdSec takes that one step further by recording that IP and distributing it to all other machines running that service. Meaning that attacker would be banned from another machine before even attempting to attack it.

Contributors & maintainers: blotus, buxior & Jdv / CrowdSec SAS, 86 Contributors]

Activity: 162 Commits over 6 months (adv 27/Mth), 224 Open Issues / 1,018 Closed Issues (~22% of all Issues are Open) and they are currently at v1.8.1 (over 223 Releases)

Popularity: 14.8K stars, 715 forks, Depends on Docker, Golang(Go), Grok Patterns, SSH, Sqlite

Languages: 
 - Go 83.2%
 - Shell 11.7%
 - Python 1.4%
 - Go Template 1.3%
 - HTML .7%
 - MakeFile .7%

supported platforms: Checkpoint, Cisco, F5, Foritnet, Juniper, Mikrotik OPNsense, PaloAlto, pfSense, Sophos
                      Linux, FreeBSD, Windows, Docker, Kubernetes, WHM, Unix Firewall, NGinx HAproxy, cloudflare workers 

Documentation: [official docs site, wiki, README quality]
[Official Docs](https://doc.crowdsec.net/u/blocklists/security_engine)
 - Great Documentation and Wiki Built together
[Wiki](https://doc.crowdsec.net/)
[ReadMe](https://github.com/crowdsecurity/crowdsec?tab=security-ov-file)
 - Overall Introduction to how Crowd-sec works

6. License, Contribution Procedures, and Contributor Agreements

(Issue #7)

License: [license name — confirm it's OSI-recognized open source]

What it permits/requires: [modification, redistribution, commercial use, copyleft implications]

Contribution process: [summary of CONTRIBUTING.md — PR process, code review norms, testing/style requirements]

Contributor agreement: [CLA or DCO requirement, if any]

7. Security-Related History

(Issue #8)

[3–5 notable CVEs or security advisories: what the vulnerability was, severity, how/when it was fixed. Plus any notable security-driven design decisions — features added, removed, or hardened for security reasons.]

8. Reflection

(Issue #9)

Individual reflections (what did you learn from this assignment? what did you find most useful?)

Mujib: [reflection]
Kowshik: [reflection]
Leonard: [reflection]
Trung: [reflection]
Hrudhay: [reflection]

Team reflection (compiled):

[Synthesized summary of the above — not just a list of quotes.]
