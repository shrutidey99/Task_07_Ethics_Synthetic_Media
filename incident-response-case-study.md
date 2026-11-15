# Incident-Response Case Study: Misleading Synthetic Career Guidance

## Introduction

This case study examines how a university Career Services office should respond when misleading synthetic media is distributed using the appearance and authority of an official university communication.

The earlier phases of this project established ethical principles, a synthetic-media governance policy, a real-world Career Services case study, and a compliance-audit framework. This case study moves the project into incident response by testing whether those controls remain useful after harmful content has already been distributed.

The scenario is hypothetical. It does not describe an actual university, employee, or incident.

## Organizational Context

Northbridge University operates a Career Services office that supports undergraduate, graduate, and international students. The office publishes workshop announcements, résumé guidance, interview preparation materials, and general employment information through its website, email newsletters, and social-media accounts.

Career Services previously adopted a synthetic-media policy permitting limited uses of generic AI presenters for low-risk information. The policy prohibits:

- Impersonating identifiable people
- Fabricating university guidance
- Providing individualized immigration or legal advice through synthetic presenters
- Publishing realistic synthetic content without disclosure
- Using synthetic media without an accountable human owner
- Removing disclosure or provenance information

## Incident Scenario

On a Monday morning, students begin sharing a 45-second video through WhatsApp groups, Instagram, and TikTok. The video features a realistic presenter sitting in a university-style office with Northbridge University branding in the background.

The presenter claims to speak on behalf of Career Services and provides incorrect employment guidance for international students. The video states that students can accept any unpaid position to satisfy employment requirements without first confirming whether the position is connected to their academic program.

The presenter is not a real Career Services employee. The face, voice, office, and speech are AI-generated. The video contains no synthetic-media disclosure.

The video also includes:

- The university logo
- A copied Career Services email address
- A registration link leading to an unofficial website
- Captions designed to resemble official university content
- A title stating “Important Career Services Update”

Within four hours, the video receives approximately 8,000 views. Several students contact Career Services asking whether the information is accurate. One student reports having already contacted an unpaid employer based on the video.

## Initial Risk Assessment

The incident creates several overlapping risks.

| Risk | Description | Severity |
|---|---|---|
| Misinformation | Students may rely on incorrect employment guidance | Critical |
| False authority | The video appears to represent the university | Critical |
| Student harm | International students may make decisions affecting their status or employment | Critical |
| Impersonation | The synthetic presenter falsely represents Career Services | High |
| Brand misuse | University branding creates apparent legitimacy | High |
| Phishing | The unofficial registration link may collect student information | Critical |
| Disclosure failure | The realistic synthetic presenter is not labeled | High |
| Trust erosion | Students may become uncertain about legitimate university communications | High |
| Operational disruption | Staff must redirect resources toward verification and response | Medium |

The incident should be classified as critical because the content combines synthetic impersonation, false institutional authority, high-stakes guidance, and possible data collection.

## Incident Timeline

### 9:00 a.m. — Initial Report

A student emails Career Services with a link to the video and asks whether the information is official.

### 9:15 a.m. — Internal Verification

The communications coordinator checks official publication records and confirms that Career Services did not create or approve the video.

The office also confirms that:

- The presenter is not an employee
- The script was not reviewed by Career Services
- The linked website is not university-controlled
- The video does not appear in the approved synthetic-media project register

### 9:30 a.m. — Incident Escalation

The Director of Career Services activates the synthetic-media incident-response process and notifies:

- University Communications
- Information Security
- Privacy and Legal teams
- International Student Services
- The university’s social-media team
- The university IT help desk

A single incident owner is assigned to coordinate the response.

### 10:00 a.m. — Evidence Preservation

Before requesting removal, the response team preserves:

- The original video
- Screenshots of posts and comments
- URLs and account names
- Upload timestamps
- View and engagement counts
- Copies of the unofficial website
- The registration form
- Student reports
- Platform correspondence
- Available metadata

Preserving evidence is important because accounts, websites, and media may disappear after takedown requests are submitted.

### 10:30 a.m. — Public Correction

Career Services publishes an urgent correction through its official website, email list, Instagram account, and student portal.

The correction states:

> A video currently circulating online that claims to provide employment guidance from Northbridge University Career Services is not an official university communication. The presenter and voice are AI-generated, and the information was not created, reviewed, or approved by Career Services. Students should not submit information through the linked website. Please use the official Career Services and International Student Services channels for guidance.

The office avoids reposting the misleading video unnecessarily because doing so could increase its reach.

### 11:00 a.m. — Student Support

Career Services and International Student Services establish a dedicated contact channel for students who:

- Relied on the video
- Submitted personal information
- Contacted an employer because of the guidance
- Need help verifying legitimate employment information
- Are unsure whether another communication is authentic

High-stakes questions are handled by qualified human staff rather than automated systems.

### 11:30 a.m. — Platform and Domain Response

University Communications submits impersonation and misinformation reports to each platform.

Information Security:

- Reports the unofficial website
- Investigates the domain registration
- Blocks the domain on university networks when appropriate
- Checks whether university credentials were collected
- Searches for similar copies or related accounts

### 1:00 p.m. — Scope Assessment

The response team determines:

- How many versions exist
- Whether the video was translated
- Which student groups received it
- Whether any personal information was collected
- Whether similar content targets other departments
- Whether an internal account or file was compromised
- Whether the video reused any authentic Career Services material

### End of Day — Response Review

The university documents current findings, unresolved risks, removal status, student impact, and next actions. Monitoring continues until the major copies and unofficial website are addressed.

## Application of the Phase B Policy

### Prohibited Use

The video violates multiple policy requirements because it:

- Falsely claims institutional approval
- Delivers high-stakes guidance through a synthetic presenter
- Uses university branding without authorization
- Contains no synthetic-media disclosure
- Has no accountable human owner
- Was not reviewed or approved
- Directs students to an unofficial data-collection website

The project would never have been eligible for approval under the Career Services policy.

### Human Accountability

The synthetic presenter creates the appearance of a responsible speaker without providing anyone who can be questioned or held accountable.

The incident response restores accountability by naming a real university official as the response owner and giving students access to qualified human staff.

### Disclosure

A synthetic-media label would have reduced confusion, but disclosure alone would not have made the video acceptable. The content would still contain false guidance, unauthorized branding, and possible phishing.

This demonstrates an important governance principle:

> Disclosure is a safeguard, not permission to create harmful or deceptive content.

### Provenance

The absence of valid university publication records and provenance supports the conclusion that the video is unofficial. However, missing Content Credentials alone cannot prove that content is false.

Verification must combine:

- Official publication history
- Approved project records
- University-controlled accounts
- Retained source files
- Human confirmation
- Technical investigation

### Detection

Automated deepfake detection may assist the investigation, but it should not determine the response. Task 6 demonstrated that a detector can return inconclusive results even when a video is fully synthetic.

The response should focus on whether the university created and approved the message—not only whether software identifies it as AI-generated.

## Governance Audit Findings

The incident can be evaluated against the Governance Audit and Compliance Checklist.

| Control Area | Result | Explanation |
|---|---|---|
| Human ownership | Failed | No accountable university owner |
| Use classification | Failed | Prohibited high-stakes synthetic guidance |
| Script accuracy | Failed | Information was not verified |
| Consent | Not applicable | Presenter was synthetic, but university identity was misappropriated |
| Student data | Critical concern | Unofficial website may have collected information |
| Disclosure | Failed | No synthetic-media disclosure |
| Provenance | Failed | No authorized production record |
| Review and approval | Failed | No university approval |
| Vendor governance | Unknown | Generation tool and creator are unidentified |
| Publication controls | Failed | Distributed through unofficial channels |
| Accessibility | Not a mitigating factor | Captions increased reach but not legitimacy |
| Incident response | Activated | University response procedures were used |

The project receives a critical noncompliance rating regardless of any numerical score because it triggers several automatic-failure conditions.

## Root-Cause Analysis

Although the creator caused the incident, the university should examine why the content was convincing and why students had difficulty verifying it.

Possible contributing factors include:

1. Students were unfamiliar with official Career Services communication channels.
2. University branding was easy to copy.
3. Career guidance was already distributed across multiple platforms.
4. No public verification page existed for official videos.
5. Students were not trained to recognize synthetic impersonation.
6. The university lacked a simple method for reporting suspicious content.
7. High-stakes guidance was not consistently accompanied by official-source reminders.
8. Synthetic-media incidents had not been included in previous response exercises.

The university cannot prevent every external fabrication, but it can reduce confusion and improve response speed.

## Corrective Actions

### Immediate Actions

- Remove or report known copies
- Disable or report the unofficial website
- Notify affected students
- Correct the false guidance
- Preserve evidence
- Investigate possible data exposure
- Monitor for additional copies

### Short-Term Actions

- Create a public page listing verified Career Services channels
- Add an easy “Report suspicious content” form
- Train staff to escalate synthetic impersonation reports
- Publish guidance explaining how students can verify official messages
- Coordinate response procedures with International Student Services
- Add synthetic-media incidents to phishing-awareness materials

### Long-Term Actions

- Conduct annual synthetic-media incident exercises
- Maintain a registry of official synthetic-media projects
- Use consistent disclosure on legitimate AI-generated content
- Preserve Content Credentials when supported
- Monitor copied university branding
- Review third-party platform reporting procedures
- Include synthetic impersonation in institutional risk planning
- Measure response time, removal success, and student impact

## Response Performance Measures

The university should track:

- Time from first report to verification
- Time from verification to public correction
- Number of platforms notified
- Number of copies removed or labeled
- Number of students who submitted information
- Number of students who relied on the guidance
- Time required to disable the unofficial website
- Number of student-support requests
- Number of repeated or derivative videos
- Completion rate for corrective actions

These measures determine whether the response process works operationally rather than merely existing on paper.

## Key Findings

This case study produces five major findings.

### 1. Authenticity and Accuracy Are Different

A message can look authentic while being false. A legitimate university source can also publish inaccurate information. Verification must examine both origin and content.

### 2. Disclosure Is Necessary but Insufficient

A label would identify the video as synthetic, but it would not correct false guidance, unauthorized branding, or phishing.

### 3. Detection Cannot Carry the Decision

An inconclusive detector result should not delay correction when university records already show that the content is unauthorized.

### 4. High-Stakes Guidance Requires Human Accountability

Students need access to a qualified person who can answer questions, correct mistakes, and take responsibility for the message.

### 5. Governance Must Include Response, Not Only Prevention

Policies often focus on approval before publication. External actors will not follow internal policy. Responsible governance must therefore include verification, monitoring, correction, takedown, student support, and recovery.

## Conclusion

This scenario demonstrates how synthetic media can combine visual credibility, institutional branding, false information, and rapid distribution to create a high-risk incident.

The Phase B policy provides the boundaries needed to classify the video as prohibited. The Governance Audit identifies the failed controls. The incident-response process translates those findings into action.

No policy can prevent every external actor from creating deceptive synthetic media. However, an organization can reduce harm by maintaining authoritative records, responding quickly, preserving evidence, issuing clear corrections, supporting affected students, and assigning real human accountability.

The main lesson is that synthetic-media governance cannot end when content is published. It must continue through verification, monitoring, incident response, correction, and institutional learning.
