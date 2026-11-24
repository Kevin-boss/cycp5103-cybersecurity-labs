# LinkedIn post templates (150-200 words each)

Structure: Hook (a finding) > What I did > What I learned (2-3 points) > Repo link > Hashtags
Hashtags: #Cybersecurity #BlueTeam #SOC #LearningInPublic

## Post 0 - Kick-off (25 Nov)
Starting a 2-week hands-on cybersecurity lab series for my Master's course on Advanced Cybersecurity Principles.
Everything runs in a controlled lab I own, and every write-up covers scope, evidence, findings, and defensive recommendations.
First up: a safe ransomware simulation. Follow along: <repo link>

## Post 1 - Ransomware simulation
Hook: "No malware. One renamed file. And the clinic's appointments 'disappeared'."
- Availability is the first thing ransomware attacks
- A backup you never test is a hope, not a control
- Offline/versioned backups + least privilege + staff awareness
Repo: <link/01-ransomware-simulation>

## Post 2 - SOC log
Hook: "Three failed logins, then a success. Compromise, or a forgetful student?"
- Triage before assuming
- Alert thresholds + MFA + human review before blocking
Repo: <link/03-soc-log-investigation>

## Post 3 - Passive footprinting
Hook: "I learned a lot about a domain without sending a single probe at it."
- DNS and public records reveal more than most orgs expect
- Passive vs active: scope is everything
Repo: <link/04-passive-footprinting>

## Post 4 - Nmap
Hook: "An open port is not a vulnerability."
- Ports show exposure; evidence shows risk
- Only scan what you own or are authorised to test
Repo: <link/05-nmap-local-lab>

## Post 5 - Anonymity tool
Hook: "The tool said every module was enabled. The leak test said 'Not Protected'."
- Status screens are claims, not proof
- Baseline, test independently, compare after stopping
Repo: <link/07-anonymity-whoami>

## Post 6 - Phishing awareness
Hook: "Urgency, a link, and a request for a code. The three-part pattern behind most scams."
- Verify via official channels; never share OTPs
- MFA, SPF/DKIM/DMARC, easy reporting
Repo: <link/08-phishing-awareness>
