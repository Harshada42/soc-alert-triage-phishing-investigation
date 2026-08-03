# TryHackme

# SOC Alert Triage and Phishing Investigation Lab

## Overview

This repository documents a hands-on Security Operations Center investigation
completed through the TryHackMe SOC Simulator.

The scenario involved reviewing simulated phishing and firewall alerts,
identifying malicious activity, classifying alerts, documenting investigation
findings, and recommending appropriate response actions.

This was a simulated training environment and did not involve a real security
incident or production system.

## Scenario Objectives

- Review incoming security alerts
- Identify true-positive security events
- Investigate suspicious email links and blocked external URLs
- Determine whether the observed activity was malicious or benign
- Document the affected entities, evidence, potential impact, and response
- Improve investigation speed and reporting quality

## Alert Categories Investigated

### Phishing Alerts

Alert rule:

`Inbound Email Containing Suspicious External Link`

The investigation focused on determining whether an external link delivered
through email represented malicious phishing activity.

### Firewall Alert

Alert rule:

`Access to Blacklisted External URL Blocked by Firewall`

The investigation focused on reviewing an attempted connection to a
blacklisted external destination and determining the associated security risk.

## Investigation Workflow

1. Reviewed the alert name, severity, timestamp, and source.
2. Identified the affected user, host, email, or network entity where available.
3. Examined the suspicious URL and related activity.
4. Correlated available email, firewall, endpoint, and network information.
5. Assessed whether the behaviour was expected or suspicious.
6. Classified the alert based on the available evidence.
7. Documented the findings and potential impact.
8. Recommended containment, escalation, or closure actions.

## Scenario Results

- Alerts investigated: 5
- True-positive identification rate: 100%
- Mean time to resolve: 13 minutes
- Mean dwell time: 21 minutes
- Scenario points: 125
- Alert types: Phishing and Firewall

The scenario reported a 100% overall true-positive identification rate.
However, two individual alert analyses were marked incorrect. These results
were reviewed as learning opportunities to improve evidence interpretation and
incident-reporting quality.

## Skills Demonstrated

- SOC alert monitoring and triage
- Phishing alert investigation
- Suspicious URL analysis
- Firewall alert analysis
- True-positive and false-positive classification
- Incident documentation
- Security event prioritisation
- Mean Time to Resolve analysis
- Escalation and response recommendations
- Clear technical reporting

## Reporting Improvements

The simulator feedback indicated that the reports successfully identified the
affected entities and malicious activity.

The main improvement areas were:

- Explaining why the activity was malicious
- Describing the potential impact of the URL or event
- Providing more detail about who was affected
- Identifying where the activity occurred
- Improving the context surrounding the timeline

Future reports will follow the 5W1H structure:

- What happened?
- When did it happen?
- Where did it happen?
- Who was affected?
- Why is it considered suspicious?
- How should the incident be handled?

## Evidence

### Scenario Completion

![Scenario completion](evidence/scenario-completion.png)

### Investigation Results

![Alert analysis](evidence/alert-analysis.png)

### Performance Metrics

![Performance metrics](evidence/performance-metrics.png)

## Disclaimer

This repository documents a cybersecurity training exercise completed in a
simulated SOC environment. All events, users, systems, and incidents were part
of the simulation.

https://tryhackme.com/soc-sim/public-summary/4c56e7fa3931a1d86732297708cb6630a63a2a516bdbfa21e8df62b2a122efec5d6f317f41056c028b3c5a8993998619


