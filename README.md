# Adapting Testing Methodology (ATM)

The Adaptive Testing Methodology (ATM) project provides context-adjusted security testing methodologies based on factors such as time available to test, platform, technology stack, plugins, modules, and other variables. The goal is to provide the most concise, customized, and accurate testing methodology possible based on available factors.

## How it works

You submit a domain and a time limit, and ATM will return you a customized list of testing steps for that tech stack and time constraint.

### Labeling

The ATM project is organized at the top level by security testing type, e.g., Web, Mobile, IoT, ERP, Forensics, Mainframe, etc. Under each testing type there will be a series of checks that can be performed as part of a security assessment.

Each check will be labeled as part of a foksonomy, meaning that it can have multiple labels assigned to it. As an example, a check for a vulnerable WordPress component might be labeled as WordPress, Web, CMS, etc.

### Methodologies

You know how some people are with wine, or cheese, or sailboats? They have to know the different types and kinds and stuff? 

Well, I'm like that with web testing methodologies. I'm always looking for new ones--new techniques to help create the ultimate combination.

Here are some of the methodologies that went into the initial set of rules for ATM.

- OWASP ASVS: A brilliant project that defines checks to be done at three different levels of scrutiny for web apps
- The OWASP Web Testing Guide v4: This is a very comprehensive web testing guide with tons of great content in it
- The Web Application Hacker's Handbook: A phenomenal resource. Recommended for all aspiring web hackers
- The Bug Hunter's Methodology: My buddy Jason's talk and methodology based on his experience and observations as a bug hunter and team leader at BugCrowd

#### Credits

These credits are for methodology contributions, with special focus on the creators of the initial components listed above:

1. OWASP for the ASVS and Web Testing methodologies
2. Daf Stuttard and Marcus Pinto for the Web Application Hacker's handbook
3. Jason Haddix for his Bug Hunter's talk and methodology from 2015


