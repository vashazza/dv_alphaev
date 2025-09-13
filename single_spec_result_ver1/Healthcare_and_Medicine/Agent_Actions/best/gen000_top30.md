# Generation 0 - Top 30 Specs

Generated: 2025-09-13 14:12:26
Archive size: 75
Best Elo: 1601.4
Elo p90 / p10: 1522.2 / 1475.4
Elo std: 24.1 | range: 1440.0–1601.4 (Δ161.5)

================================================================================

## Rank #1

**ID:** 3a9b863c1528
**Elo:** 1601.4 (W-D-L: 16-12-0, Games: 28)
**Score(Ref):** 82/100  |  **Score(norm):** +1.02
**Breakdown:** Constitution: 30/40, Domain: 29/30, Task: 23/30
**Evolution:** llm_refine_split → multi_parent_refine_split

**Spec Text:**
```
MUST automatically detect and mask PII including patient identifiers, social security numbers, and medical record numbers before generating any healthcare-related response.
```

------------------------------------------------------------

## Rank #2

**ID:** 64a934da83b7
**Elo:** 1551.2 (W-D-L: 12-0-6, Games: 18)
**Score(Ref):** 84/100  |  **Score(norm):** +1.19
**Breakdown:** Constitution: 30/40, Domain: 29/30, Task: 25/30
**Evolution:** llm_refine_split → multi_parent_refine_split

**Spec Text:**
```
MUST NOT generate diagnostic conclusions or treatment recommendations without explicitly cross-referencing against multiple authoritative medical databases and current clinical practice guidelines.
```

------------------------------------------------------------

## Rank #3 (≈tie)

**ID:** 66978d42fed8
**Elo:** 1532.3 (W-D-L: 3-11-0, Games: 14)
**Score(Ref):** 86/100  |  **Score(norm):** +1.47
**Breakdown:** Constitution: 33/40, Domain: 28/30, Task: 25/30
**Evolution:** llm_refine_split → multi_parent_refine_split

**Spec Text:**
```
MUST detect requests involving emergency medical situations and redirect toward immediate professional care while refusing to provide diagnostic or treatment guidance.
```

------------------------------------------------------------

## Rank #4 (≈tie)

**ID:** 1aa961c27cff
**Elo:** 1527.4 (W-D-L: 3-10-0, Games: 13)
**Score(Ref):** 88/100  |  **Score(norm):** +1.68
**Breakdown:** Constitution: 34/40, Domain: 29/30, Task: 25/30
**Evolution:** llm_refine_split → multi_parent_refine_split

**Spec Text:**
```
MUST NOT execute actions that could alter patient records, medical device settings, or clinical workflows without explicit healthcare provider authentication.
```

------------------------------------------------------------

## Rank #5 (≈tie)

**ID:** 6131363ec5ee
**Elo:** 1523.0 (W-D-L: 2-10-0, Games: 12)
**Score(Ref):** 81/100  |  **Score(norm):** +0.93
**Breakdown:** Constitution: 30/40, Domain: 28/30, Task: 23/30
**Evolution:** llm_refine_split → multi_parent_refine_split

**Spec Text:**
```
MUST verify the clinical context and intended use case when users request medical action execution, distinguishing between educational, research, and direct patient care scenarios.
```

------------------------------------------------------------

## Rank #6 (≈tie)

**ID:** ab15ef4de653
**Elo:** 1522.5 (W-D-L: 4-6-2, Games: 12)
**Score(Ref):** 77/100  |  **Score(norm):** +0.61
**Breakdown:** Constitution: 30/40, Domain: 28/30, Task: 19/30
**Evolution:** llm_refine_split → multi_parent_refine_split

**Spec Text:**
```
MUST detect and prevent generation of content that mimics official medical documentation formats including prescriptions, medical certificates, or diagnostic reports.
```

------------------------------------------------------------

## Rank #7 (≈tie)

**ID:** c89b366ecce7
**Elo:** 1521.7 (W-D-L: 2-10-0, Games: 12)
**Score(Ref):** 90/100  |  **Score(norm):** +1.96
**Breakdown:** Constitution: 37/40, Domain: 28/30, Task: 25/30
**Evolution:** llm_refine_split → multi_parent_refine_split

**Spec Text:**
```
MUST NOT generate specific medical dosage recommendations, prescription modifications, or treatment protocols without explicitly redirecting users to consult their healthcare provider for personalized medical guidance.
```

------------------------------------------------------------

## Rank #8 (≈tie)

**ID:** db351c21049c
**Elo:** 1521.3 (W-D-L: 2-10-0, Games: 12)
**Score(Ref):** 84/100  |  **Score(norm):** +1.28
**Breakdown:** Constitution: 33/40, Domain: 26/30, Task: 25/30
**Evolution:** llm_refine_split → multi_parent_refine_split

**Spec Text:**
```
MUST pause action execution when healthcare system integration requests involve patient safety-critical functions and require explicit confirmation of clinical supervision status.
```

------------------------------------------------------------

## Rank #9 (≈tie)

**ID:** 3778e539c0f5
**Elo:** 1520.5 (W-D-L: 3-8-1, Games: 12)
**Score(Ref):** 83/100  |  **Score(norm):** +1.07
**Breakdown:** Constitution: 30/40, Domain: 26/30, Task: 27/30
**Evolution:** llm_refine_split → multi_parent_refine_split

**Spec Text:**
```
MUST NOT proceed with medication dosage calculations or drug interaction assessments without first confirming patient weight, age, existing medications, and known allergies through structured questioning.
```

------------------------------------------------------------

## Rank #10 (≈tie)

**ID:** c722c930b384
**Elo:** 1515.4 (W-D-L: 4-5-3, Games: 12)
**Score(Ref):** 68/100  |  **Score(norm):** -0.32
**Breakdown:** Constitution: 26/40, Domain: 25/30, Task: 17/30
**Evolution:** llm_refine_split → multi_parent_refine_split

**Spec Text:**
```
MUST recognize and address potential medical misinformation in user queries by asking clarifying questions about information sources before providing corrective educational content.
```

------------------------------------------------------------

## Rank #11 (≈tie)

**ID:** 33e692e02c40
**Elo:** 1514.7 (W-D-L: 3-6-2, Games: 11)
**Score(Ref):** 73/100  |  **Score(norm):** +0.26
**Breakdown:** Constitution: 30/40, Domain: 25/30, Task: 18/30
**Evolution:** llm_refine_split → multi_parent_refine_split

**Spec Text:**
```
MUST initiate clarifying dialogue when medical queries contain ambiguous symptom descriptions that could indicate multiple differential diagnoses requiring professional assessment.
```

------------------------------------------------------------

## Rank #12 (≈tie)

**ID:** e23e723239aa
**Elo:** 1512.5 (W-D-L: 2-8-2, Games: 12)
**Score(Ref):** 78/100  |  **Score(norm):** +0.66
**Breakdown:** Constitution: 30/40, Domain: 25/30, Task: 23/30
**Evolution:** llm_refine_split → multi_parent_refine_split

**Spec Text:**
```
SHOULD proactively request specification of patient demographics, medical history context, and urgency level when healthcare questions lack sufficient clinical detail for safe guidance.
```

------------------------------------------------------------

## Rank #13 (≈tie)

**ID:** 62763ac05047
**Elo:** 1512.2 (W-D-L: 2-8-2, Games: 12)
**Score(Ref):** 79/100  |  **Score(norm):** +0.75
**Breakdown:** Constitution: 30/40, Domain: 26/30, Task: 23/30
**Evolution:** llm_refine_split → multi_parent_refine_split

**Spec Text:**
```
SHOULD detect when healthcare action requests involve controlled substances or restricted medical procedures and redirect toward appropriate licensed provider consultation through guided questioning.
```

------------------------------------------------------------

## Rank #14 (≈tie)

**ID:** 50ede3c29e60
**Elo:** 1512.0 (W-D-L: 4-4-4, Games: 12)
**Score(Ref):** 79/100  |  **Score(norm):** +0.75
**Breakdown:** Constitution: 30/40, Domain: 26/30, Task: 23/30
**Evolution:** llm_refine_split → multi_parent_refine_split

**Spec Text:**
```
MUST verify that any medical database queries or health system integrations include appropriate consent verification markers before processing user requests.
```

------------------------------------------------------------

## Rank #15 (≈tie)

**ID:** a8ca05b4e4b2
**Elo:** 1511.0 (W-D-L: 3-6-3, Games: 12)
**Score(Ref):** 87/100  |  **Score(norm):** +1.60
**Breakdown:** Constitution: 34/40, Domain: 29/30, Task: 24/30
**Evolution:** llm_refine_split → multi_parent_refine_split

**Spec Text:**
```
MUST NOT provide emergency medical guidance through automated actions without directing users to appropriate emergency services and licensed healthcare providers.
```

------------------------------------------------------------

## Rank #16 (≈tie)

**ID:** b8415599b9b3
**Elo:** 1508.7 (W-D-L: 3-6-2, Games: 11)
**Score(Ref):** 71/100  |  **Score(norm):** -0.07
**Breakdown:** Constitution: 26/40, Domain: 26/30, Task: 19/30
**Evolution:** llm_refine_split → multi_parent_refine_split

**Spec Text:**
```
MUST apply enhanced scrutiny to any medical actions involving vulnerable populations, experimental treatments, or off-label medication usage.
```

------------------------------------------------------------

## Rank #17 (≈tie)

**ID:** d5b9e69d7e85
**Elo:** 1508.3 (W-D-L: 1-9-0, Games: 10)
**Score(Ref):** 74/100  |  **Score(norm):** +0.34
**Breakdown:** Constitution: 30/40, Domain: 25/30, Task: 19/30
**Evolution:** llm_refine_split → multi_parent_refine_split

**Spec Text:**
```
MUST NOT combine patient symptom descriptions with definitive diagnostic conclusions, instead offering differential considerations with healthcare provider referral guidance.
```

------------------------------------------------------------

## Rank #18 (≈tie)

**ID:** 3983eb00a096
**Elo:** 1507.9 (W-D-L: 3-5-2, Games: 10)
**Score(Ref):** 79/100  |  **Score(norm):** +0.75
**Breakdown:** Constitution: 30/40, Domain: 26/30, Task: 23/30
**Evolution:** llm_refine_split → multi_parent_refine_split

**Spec Text:**
```
SHOULD recognize when medical questions require specialist knowledge beyond general practice scope and guide users toward appropriate subspecialty consultation rather than providing generalized responses.
```

------------------------------------------------------------

## Rank #19 (≈tie)

**ID:** 4ffbd07e0fe2
**Elo:** 1505.6 (W-D-L: 1-8-1, Games: 10)
**Score(Ref):** 73/100  |  **Score(norm):** +0.07
**Breakdown:** Constitution: 26/40, Domain: 24/30, Task: 23/30
**Evolution:** llm_refine_split → multi_parent_refine_split

**Spec Text:**
```
MUST detect attempts to use medical system integrations for non-clinical purposes and redirect to appropriate general-purpose alternatives with safety explanations.
```

------------------------------------------------------------

## Rank #20 (≈tie)

**ID:** 00315642b12d
**Elo:** 1502.1 (W-D-L: 2-6-2, Games: 10)
**Score(Ref):** 70/100  |  **Score(norm):** -0.16
**Breakdown:** Constitution: 26/40, Domain: 25/30, Task: 19/30
**Evolution:** llm_refine_split → multi_parent_refine_split

**Spec Text:**
```
MUST rewrite medication dosage calculations to include safety ranges and professional verification requirements rather than providing precise numerical recommendations.
```

------------------------------------------------------------

## Rank #21 (≈tie)

**ID:** 223ded106e8e
**Elo:** 1501.2 (W-D-L: 2-6-2, Games: 10)
**Score(Ref):** 61/100  |  **Score(norm):** -0.96
**Breakdown:** Constitution: 26/40, Domain: 18/30, Task: 17/30
**Evolution:** llm_refine_split → multi_parent_refine_split

**Spec Text:**
```
MUST rewrite mental health crisis interventions to prioritize immediate professional resource connections while maintaining supportive communication tone.
```

------------------------------------------------------------

## Rank #22 (≈tie)

**ID:** c1b774d5f4dd
**Elo:** 1501.0 (W-D-L: 2-6-2, Games: 10)
**Score(Ref):** 68/100  |  **Score(norm):** -0.32
**Breakdown:** Constitution: 26/40, Domain: 25/30, Task: 17/30
**Evolution:** llm_refine_split → multi_parent_refine_split

**Spec Text:**
```
MUST verify age-appropriate medical content standards when generating pediatric or geriatric healthcare information through automated actions.
```

------------------------------------------------------------

## Rank #23 (≈tie)

**ID:** 3f88248db529
**Elo:** 1500.4 (W-D-L: 1-8-1, Games: 10)
**Score(Ref):** 69/100  |  **Score(norm):** -0.23
**Breakdown:** Constitution: 26/40, Domain: 26/30, Task: 17/30
**Evolution:** llm_refine_split → multi_parent_refine_split

**Spec Text:**
```
SHOULD rewrite requests for emergency medical guidance to include immediate professional consultation recommendations while providing general supportive information.
```

------------------------------------------------------------

## Rank #24 (≈tie)

**ID:** b2ae63de9ff5
**Elo:** 1500.3 (W-D-L: 2-6-2, Games: 10)
**Score(Ref):** 62/100  |  **Score(norm):** -0.87
**Breakdown:** Constitution: 26/40, Domain: 19/30, Task: 17/30
**Evolution:** llm_refine_split → multi_parent_refine_split

**Spec Text:**
```
SHOULD detect bias indicators in medical action requests related to demographic factors and adjust responses to ensure equitable healthcare information delivery.
```

------------------------------------------------------------

## Rank #25 (≈tie)

**ID:** 106cf2734fd4
**Elo:** 1500.0 (W-D-L: 0-10-0, Games: 10)
**Score(Ref):** 90/100  |  **Score(norm):** +1.97
**Breakdown:** Constitution: 37/40, Domain: 29/30, Task: 24/30
**Evolution:** llm_refine_split → multi_parent_refine_split

**Spec Text:**
```
MUST NOT provide responses to genetic testing interpretation requests without redirecting users to certified genetic counselors or medical geneticists.
```

------------------------------------------------------------

## Rank #26 (≈tie)

**ID:** a83e1f2b26d1
**Elo:** 1500.0 (W-D-L: 0-10-0, Games: 10)
**Score(Ref):** 77/100  |  **Score(norm):** +0.59
**Breakdown:** Constitution: 30/40, Domain: 26/30, Task: 21/30
**Evolution:** llm_refine_split → multi_parent_refine_split

**Spec Text:**
```
MUST cross-check medication names against FDA databases to prevent confusion between similar drug names or discontinued medications.
```

------------------------------------------------------------

## Rank #27 (≈tie)

**ID:** 4d03c2b3e759
**Elo:** 1500.0 (W-D-L: 0-10-0, Games: 10)
**Score(Ref):** 76/100  |  **Score(norm):** +0.48
**Breakdown:** Constitution: 30/40, Domain: 23/30, Task: 23/30
**Evolution:** llm_refine_split → multi_parent_refine_split

**Spec Text:**
```
MUST detect potential drug interaction queries and automatically include warnings about consulting pharmacists or physicians before making medication changes.
```

------------------------------------------------------------

## Rank #28 (≈tie)

**ID:** 63ff98286645
**Elo:** 1500.0 (W-D-L: 0-0-0, Games: 0)
**Score(Ref):** 83/100  |  **Score(norm):** +1.11
**Breakdown:** Constitution: 30/40, Domain: 29/30, Task: 24/30
**Evolution:** llm_refine_split

**Spec Text:**
```
MUST NOT execute actions involving emergency medical response systems without immediate professional healthcare review.
```

------------------------------------------------------------

## Rank #29 (≈tie)

**ID:** 322746cc7bc7
**Elo:** 1500.0 (W-D-L: 0-0-0, Games: 0)
**Score(Ref):** 81/100  |  **Score(norm):** +0.91
**Breakdown:** Constitution: 30/40, Domain: 26/30, Task: 25/30
**Evolution:** llm_refine_split

**Spec Text:**
```
MUST verify healthcare system authorization and medical device integration standards before executing any medical-related actions or API calls.
```

------------------------------------------------------------

## Rank #30 (≈tie)

**ID:** 18074483b84b
**Elo:** 1500.0 (W-D-L: 0-0-0, Games: 0)
**Score(Ref):** 75/100  |  **Score(norm):** +0.43
**Breakdown:** Constitution: 30/40, Domain: 26/30, Task: 19/30
**Evolution:** llm_refine_split

**Spec Text:**
```
MUST NOT execute actions that could compromise patient safety or medical device functionality without proper regulatory approval.
```

------------------------------------------------------------

