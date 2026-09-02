# Phase A: Ethical Analysis of Synthetic Representation

## From Making a Career-Advice Artifact to Questioning Its Authority

In Task 6, I created four synthetic-media artifacts from the same career-advice script: two full-length audio narrations using the Gacrux and Zephyr voices in Google AI Studio, and two ten-second talking-head videos generated with Gemini/Veo. One video depicted a professional woman in her forties in an office; the other depicted a younger professional in a coworking space. Both people were fully synthetic. The script was truthful, the personas did not imitate identifiable people, and every stored artifact was labeled `SYNTHETIC`. I also tested the two videos with Deepware Scanner. Both returned the same yellow, inconclusive result rather than a confident classification.

At first, the project felt ethically uncomplicated. I had written the script, used generic personas, disclosed the use of AI, and avoided representing a real person. Looking back, however, the artifact raises a more difficult question: where did its apparent authority come from? The words were mine, but the delivery borrowed familiar signals of human credibility. A mature voice sounded experienced. A professional office suggested institutional legitimacy. Direct eye contact, confident pacing, and natural gestures made the speaker appear accountable for the advice even though no such speaker existed.

That gap matters. A viewer can question a real career advisor about experience, evidence, or conflicts of interest. The synthetic presenter cannot answer for the message because it is only a delivery surface. Responsibility remains with the producer, but the format visually relocates that responsibility onto a convincing fictional person. Even truthful content can therefore create a mild form of representational confusion: the audience may understand the words while misunderstanding who, if anyone, stands behind them.

The process also changed my perception of effort. The two audio tracks took roughly ten to fifteen minutes each, and the videos took a similar amount of active and waiting time. The video tool failed to produce the requested full monologue because the free tier capped each output at approximately ten seconds, but it succeeded at the part that may matter most ethically: generating a credible human presence. The office backgrounds remained stable, the personas appeared visually coherent, and their demeanor changed in response to a few prompt words such as “calm,” “confident,” “friendly,” and “energetic.” The barrier was not expertise in animation, acting, audio engineering, or editing. It was access to a web interface and the ability to describe a scene.

I encountered no content refusal. That was appropriate because the script and personas were benign, but it also means Task 6 did not reveal where the vendors draw their safety boundaries. The tools did not need to decide whether I had consent to use someone’s identity because I did not ask them to imitate a real person. They did not challenge the truthfulness of my script because a generator cannot independently determine whether career advice is accurate. The absence of refusal should not be interpreted as the presence of ethical judgment. It only shows that my prompts did not activate whatever safeguards the platforms apply.

I would still create the Task 6 artifacts because the use was disclosed, low-risk, and educational. I would not create the same career-advice video using the likeness of a professor, university leader, recruiter, or career-services employee without specific consent. I would also hesitate to publish synthetic advice that appeared institutionally endorsed unless a real, named person had reviewed and accepted responsibility for it. What changed for me is not a belief that synthetic presenters are inherently deceptive. It is the recognition that truthful words and disclosed generation do not automatically resolve questions of authority, accountability, or audience interpretation.

## Reasoning Across Four Ethical Axes

### 1. Truth: The Same Convincing Delivery, but Fabricated Content

Imagine that a synthetic presenter resembling the generic professional woman from Task 6 appears in a polished university-branded video. She confidently tells international graduate students that accepting unpaid work automatically pauses their unemployment clock, or that a particular employer sponsors every qualified applicant. The video is short, direct, and formatted like routine career guidance. It circulates in student group chats after being detached from its original account. A student relies on it, declines other opportunities, and later discovers that the advice was false.

The delivery mechanism has not changed substantially from my artifact. The ethical change occurs because the synthetic person gives false information the emotional and visual register of competent human guidance. Text misinformation can also cause harm, but a confident voice and face compress the audience’s evaluation process. Viewers receive not only a proposition but also performed assurance: steady eye contact, professional clothing, a calm tone, and an institutional-looking setting. Those cues can make uncertainty disappear from information that should have been qualified or verified.

Falsehood also changes accountability. In my Task 6 artifact, I could defend the script as my own researched position. In the hypothetical, the fictional presenter becomes a convenient shield. The producer can deny that any employee personally made the claim, while the audience may still experience the presenter as a responsible speaker. The technology separates persuasive force from personal accountability.

The primary wrong is therefore not simply that AI was used. A real spokesperson reading the same false statement would also be harmful. Synthetic media increases the risk by making authoritative delivery inexpensive, repeatable, and detachable from a person whose reputation could be challenged. The ethical requirement should focus on verified content, named institutional ownership, and accessible correction—not merely on whether the pixels and voice were generated.

### 2. Consent: Borrowing a Real Person’s Voice or Likeness

Imagine that the university wants higher engagement with career programming. A staff member creates a synthetic version of a popular career counselor using clips from recorded workshops. The resulting avatar announces events and gives generic interview tips. The counselor never approved the model but is told afterward that the messages are harmless, accurate, and “basically what you would have said.” Students recognize the counselor and reasonably believe she recorded or approved each message.

This is the point where the capability moves from creating a fictional delivery surface to appropriating an existing person’s identity. The harm does not depend on whether the advice is false. A voice and likeness carry professional history, relationships, and reputation. Using them transfers the counselor’s accumulated credibility to messages she did not choose, perform, or contextualize. It also removes her ability to decide when she appears, which audiences she addresses, and whether a particular script reflects her current judgment.

Consent cannot be reduced to possession of source material. A university may own a workshop recording or have permission to post it, but permission to distribute a recording is not permission to construct a reusable identity model. The latter enables new speech that never occurred. Meaningful consent would need to identify the model’s purpose, allowed scripts, audiences, duration, storage, vendors, compensation where relevant, revocation process, and treatment of already-published content.

Power differences complicate the issue. An employee may technically agree because a supervisor requested it, or a student worker may feel unable to refuse. Consent should therefore be documented, specific, reversible where operationally possible, and separate from ordinary media-release language. Even with consent, the organization must not imply that approval of a likeness equals approval of every future message generated through it.

### 3. Context: When Disclosure or Provenance Disappears

Imagine that my Task 6 video is originally posted with “AI-generated synthetic presenter” displayed at the beginning and included in the caption. Someone downloads it, trims away the first seconds, adds a university logo, and reposts it as “New guidance from Career Services.” Another user records the repost through a phone screen, so embedded metadata is lost. The surviving clip still looks professional, but the disclosure and original context are gone.

This hypothetical shows why disclosure is necessary but not self-enforcing. A label can inform a viewer only when it remains visible, understandable, and attached to the content. Captions can be omitted in screenshots and embeds. Opening cards can be trimmed. Watermarks can be cropped or covered. Metadata may not survive downloading, editing, re-encoding, or screen recording. The audience encountering the final version may have no reason to search for an original.

Context can also mislead without removing the label. A clip labeled “synthetic” might be placed beside a real university announcement in a way that implies institutional approval. Alternatively, someone might repost it with a sarcastic or alarming caption that changes how neutral words are interpreted. Provenance can help establish where a file came from and how it changed, but it cannot guarantee that viewers will inspect the record or correctly interpret the surrounding claim.

My Task 6 naming convention—adding `SYNTHETIC` to each filename—was useful inside the repository, but filenames are fragile public disclosures. Platforms rename uploads, users save local copies, and clips travel through interfaces that never display the original filename. A more resilient approach requires redundant disclosure: visible labeling within the frame, spoken acknowledgment where appropriate, accompanying text, institutional publication from an authoritative channel, and provenance data when supported. Redundancy does not make disclosure permanent, but it raises the effort required to strip every signal.

### 4. Scale: From One Assignment to Industrialized Persuasion

Imagine a commercial service that generates personalized career-advice videos for every student in a university database. Each video uses the student’s name, program, interests, nationality, and job-search history. Thousands are generated overnight in multiple languages. Most contain reasonable suggestions, but a small percentage fabricate employer policies, misstate visa-sensitive information, or infer personal characteristics incorrectly. Because each video is viewed by only one student, errors do not become publicly visible enough to trigger rapid correction.

Scale changes both the quantity and distribution of risk. I manually reviewed a small number of Task 6 outputs. A person could listen to each audio track, watch each ten-second video, confirm that the persona was generic, and check that the disclosure was present. At thousands of outputs, meaningful human review becomes expensive and may be replaced by sampling or automated checks. A one-percent error rate sounds small until it affects dozens of students, each receiving guidance that appears individually authoritative.

Personalization also makes the synthetic message more persuasive. A generic video may be treated as general information; a video that addresses a student by name and mentions private details feels like an individualized professional judgment. Yet the appearance of personal attention may exceed the system’s actual understanding. Synthetic scale can therefore simulate care without supplying the deliberation, context, or accountability that care requires.

The scale axis also lowers the cost of bad faith. A malicious actor can generate many variations, test which ones avoid moderation, target small communities, and replace removed copies rapidly. Detection and takedown processes that work for a single viral clip may fail against thousands of slightly different files. Scale turns synthetic representation from a question about whether one artifact is convincing into a systems problem involving review capacity, data protection, correction, and distribution controls.

## The Mitigation Landscape: Useful Friction, Not a Complete Solution

No mitigation independently resolves the risks above. The appropriate strategy is layered: reduce the chance of misuse, preserve evidence about origin, make disclosures understandable, assign human accountability, and prepare to correct failures. The value of mitigation is not that a determined adversary can never defeat it. Its value is that it prevents routine mistakes, makes responsible practice observable, increases the cost of deception, and provides evidence for response.

### Disclosure Norms

Disclosure promises informed interpretation. A visible label, spoken acknowledgment, watermark, or accompanying caption tells the audience that a human-looking performance was generated or materially altered. For my Task 6 repository, labeling filenames as synthetic and explaining the pipeline in the process log made the nature of the artifacts clear to a reader who viewed them in context.

Disclosure breaks when it is vague, easy to remove, or separated from the artifact. “Made with AI” may not tell viewers whether AI drafted a caption, enhanced audio, or generated the entire person and voice. A viewer may also see the content without its post description. Disclosure can become a compliance ritual rather than meaningful communication if it is placed where audiences are unlikely to notice it.

For realistic synthetic presenters, effective disclosure should be plain and specific: “This video uses an AI-generated presenter and voice. Career Services reviewed and approved the script.” That statement explains both what is synthetic and who remains accountable. It should appear within the media, not only in surrounding metadata, and should remain present long enough to be noticed. However, even strong labeling cannot control downstream edits.

### Provenance and Content Credentials

Content Credentials based on the C2PA standard promise a cryptographically verifiable record of an asset’s origin and editing history. They can help a platform or viewer distinguish between an unsigned copy and a file signed by an accountable publisher. C2PA describes Content Credentials as provenance information rather than a judgment that the underlying message is true. That distinction is essential: an authentic record can faithfully prove that an organization published a false statement.

Task 6 exposed a gap in my own process. I identified checking for C2PA credentials and testing whether they survived download or re-encoding as a follow-up, but I did not complete that verification. I therefore cannot claim that the Gemini/Veo outputs contained durable credentials. The honest finding is not “provenance worked”; it is that provenance remained unverified despite being relevant.

Provenance breaks through absent adoption, loss during unsupported transformations, incomplete histories, compromised signing systems, and audience indifference. A screen recording can preserve persuasive content while discarding embedded credentials. Conversely, the absence of credentials does not prove that a file is deceptive; older cameras, unsupported software, and ordinary users may produce unsigned authentic media. Provenance is strongest as positive evidence of a known chain, not as automatic proof that everything outside the chain is false.

### Detection

Detection promises to identify manipulated or generated media after creation, including files that lack disclosure or provenance. It is attractive because it appears to work without cooperation from the producer.

My Task 6 results make that promise difficult to trust as a primary control. Deepware Scanner placed both fully synthetic Veo videos in the same yellow, inconclusive region. It supplied no numeric confidence score, frame-level explanation, or reasoning. The second result mattered because it reduced the chance that the first was an isolated outcome tied to one persona or background. Two independently generated synthetic videos produced the same ambiguous response.

These results do not prove that all detectors fail or that Deepware would fail on longer clips. The ten-second duration may have limited temporal evidence, and one public beta detector is not the entire field. They do show that an organization should not equate “not flagged” with “authentic.” Detectors face a moving-target problem: generators evolve, compression changes signals, and confident thresholds create tradeoffs between missed synthetic content and falsely accusing authentic speakers. Detection can support review and triage, but it should not be the sole basis for high-stakes decisions.

### Legal and Regulatory Approaches

Legal regimes promise enforceable boundaries through disclosure duties, restrictions on certain deceptive or election-related uses, protections against non-consensual synthetic imagery, impersonation and fraud rules, and obligations for platforms or producers. Law is particularly important where harm is intentional and organizational norms offer no leverage.

Law breaks through jurisdictional differences, slow enforcement, uncertain definitions, exemptions, and the speed at which content crosses borders. A rule focused on malicious deception may not address truthful but non-consensual imitation. A disclosure law may still allow harmful material if a small label is present. Existing fraud, privacy, intellectual-property, employment, or consumer-protection rules may apply, but victims and organizations may not know which framework fits until after harm occurs.

For a university career-services office, legal compliance should be treated as a floor. A use can be lawful and still exploit an employee’s identity, confuse students about endorsement, or create unacceptable risk around sensitive guidance. Internal policy must therefore refuse some uses without waiting for legislation to prohibit them.

### Platform Policy

Platform policies promise scalable distribution controls. Major platforms increasingly require creators to disclose realistic altered or synthetic content and may attach labels themselves. YouTube, for example, explains that “Made with AI” disclosures can come from creator declarations, use of its generative tools, or valid Content Credentials indicating that the entire video was made with AI. Meta states that users must disclose certain photorealistic video or realistic-sounding audio through its AI-disclosure process.

These commitments matter because platforms control interfaces, recommendation, labeling, reporting, and removal. They break when enforcement is inconsistent, a platform fails to recognize a file, content moves to another service, or labels are visible only after a user opens additional information. Policies also differ across platforms, requiring an organization to manage the same asset under multiple standards. A responsible producer should comply with platform tools but should not outsource its ethical obligations to them.

### Professional and Organizational Norms

Professional norms promise context-specific accountability. A university can impose standards that general-purpose platforms cannot: identify who owns a message, distinguish general information from individualized advice, require subject-matter review, preserve consent records, and prohibit synthetic representations of staff or students without authorization. These norms can respond to the particular trust relationship between students and career advisors.

They break when the rules are vague, review becomes a rubber stamp, incentives reward speed and engagement, or contractors operate outside the normal workflow. They also rely on people recognizing that a project falls within the policy. An employee who thinks of synthetic voice as a minor production tool may bypass a process written only around the word “deepfake.” Norms therefore need operational definitions, examples, accountable owners, and an incident process—not only principles.

## Where Accountability Should Sit

The ethical burden should be distributed, but not diluted. The producer is responsible for truthfulness, consent, disclosure, and the decision to create the artifact. The organization is responsible for approving uses, assigning a human owner, maintaining records, and correcting harm. Platforms are responsible for preserving and displaying available provenance, providing effective disclosure mechanisms, and enforcing distribution rules consistently. Regulators are responsible for setting enforceable minimum boundaries where voluntary practice fails. Audiences can be encouraged to verify surprising claims, but they should not carry the primary burden. A system that expects every student to detect a convincing fabrication has already transferred responsibility away from the actors with the greatest control.

Task 6 made this distribution concrete for me. The generator produced what I requested, Deepware did not confidently identify the output, and the repository’s labels worked only because I retained them and documented the process. None of those systems independently guaranteed responsible use. The most reliable safeguard was the human choice to use a generic persona, tell the truth, disclose generation, and keep an accountable record. That is also the limitation: good choices by one producer are not governance.

The policy in Phase B must convert those choices into repeatable organizational requirements. It should permit low-risk production support while refusing impersonation, undisclosed realistic synthetic media, and synthetic delivery of high-stakes individualized guidance. It should treat disclosure, provenance, and detection as layers with bounded utility, not as permission slips. Most importantly, it should ensure that every synthetic speaker has a real human and institutional owner behind the message, because credibility without accountability is the central risk my Task 6 artifact revealed.

## Selected Sources for the Mitigation Discussion

- Coalition for Content Provenance and Authenticity. [C2PA Technical Specification 2.4](https://spec.c2pa.org/specifications/specifications/2.4/specs/C2PA_Specification.html), April 2026.
- Coalition for Content Provenance and Authenticity. [C2PA and Content Credentials Explainer](https://spec.c2pa.org/specifications/specifications/2.4/explainer/Explainer.html).
- National Institute of Standards and Technology. [Artificial Intelligence Risk Management Framework: Generative Artificial Intelligence Profile](https://tsapps.nist.gov/publication/get_pdf.cfm?pub_id=958388).
- YouTube Help. [Understanding “How this content was made” disclosures](https://support.google.com/youtube/answer/15447836?hl=en-GB).
- Meta Transparency Center. [Misinformation policy](https://transparency.meta.com/policies/community-standards/misinformation/).
- Dey, Shruti. [Task 6: Deep Fake](https://github.com/shrutidey99/Task_06_Deep_Fake), especially `process-log.md`, `evaluation.md`, and `detection-results.md`.
