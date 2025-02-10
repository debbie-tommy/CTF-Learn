# Offensive Security 

Involves breaking into computer systems, exploiting software bugs, and finding loopholes in applications to gain unauthorized access.

## Gobuster- Command line app to find hidden directories and pages in a website 

Sometimes, companies may have forgotten to make certain pages private, thereby allowing hackers access to hidden pages that show or give access to Admin privileges. 

### Type in your Terminal (Source: TryHackMe.com)

gobuster -u http://fakebank.thm -w wordlist.txt dir

In the command above, -u is used to state the website we're scanning, -w takes a list of words to iterate through to find hidden pages.

You will see that Gobuster scans the website with each word in the list, finding pages that exist on the site. Gobuster will have told you the pages in the list of page/directory names (indicated by Status: 200).

If you were a penetration tester or security consultant, this is an exercise you’d perform for companies to test for vulnerabilities in their web applications and find hidden pages to investigate for vulnerabilities.

## Alt Cyber Sec Pathways:
- Red Teamer - Plays the role of an adversary, attacking an organization and providing feedback from an enemy's perspective.
- Security Engineer - Design, monitor, and maintain security controls, networks, and systems to help prevent cyberattacks.

