# Online Appendix: Sustainalyzer (ECIS 2026 Submission)

This repository contains the supplementary methodological details for the paper "Sustainalyzer – An Analysis Tool for Sustainability Communication on Social Media", addressing the space limitations of the conference format.
Concretely, the following details are addressed:

* [1. Systematic Literature Review Overview](#1-systematic-literature-review-overview)
* [2. Expert Interviews Overview](#2-expert-interviews-overview)
* [3. Design Requirements Details](#3-design-requirements-details)
* [4. References](#4-references)
  

## 1. Systematic Literature Review Overview

### 1.1 Methodology
To ensure methodological rigor, the literature review was structured following the established framework by vom Brocke et al. (2009). The process encompasses five phases:

#### *Phase 1: Definition of Review Scope*
Following Cooper’s (1988) taxonomy, the review focuses on research outcomes and methodologies at the intersection of social media analytics and sustainability communication. The goal is to integrate existing knowledge to identify critical capabilities and derive robust Design Requirements (DRs) for the proposed artifact.

#### *Phase 2: Conceptualization of Topic*
The literature search was structured around three core conceptual blocks to ensure high construct validity:
1. **Context:** Social Media (e.g., X, Twitter)
2. **Domain:** Sustainability (e.g., CSR, ESG, Triple Bottom Line)
3. **Method/Outcome:** Analytics, Text Mining, and Decision-Making Capabilities

#### *Phase 3: Literature Search*
The following table displays the used search criteria as well as guiding principles to to ensure comprehensive coverage:

| Attribute | Value |
| :--- | :--- |
| Time Period | 2015 - 2025 |
| Databases | Google Scholar, IEEE Xplore, SAGE Publications, SpringerLink, AIS Electronic Library, EBSCOhost, Emerald Insight, ACM Digital Library |
| Search Fields | Title, Abstract, Keywords|
| Search query | ("social media" OR "SM" OR "SMA") AND ("sustainab*" OR "CSR" OR "ESG" OR "Triple Bottom Line") AND ("text mining" OR "analytic*" OR "capabilit*" OR "decision making" OR "DDDM") |
| Inclusion/Exclusion Criteria | Only peer-reviewed journal and conference papers in English |


* **Forward & Backward Search:** To mitigate database bias and identify seminal cross-disciplinary works, a backward search was conducted using the visual literature mapping tool *Litmaps*.



#### *Phase 4: Literature Analysis and Synthesis (Categorization)*
To systematically synthesize the findings and derive the Design Requirements, the final literature list was analyzed using qualitative content analysis according to Mayring (2014). An inductive categorization approach was applied to extract recurring challenges, required capabilities, and strategic objectives.


#### *Phase 5: Research Agenda*
The derived DRs are used to develop the tool Sustainalyzer



## 2. Expert Interviews Overview
To elicit comprehensive and robust Design Requirements, semi-structured expert interviews were conducted. A purposive sampling strategy was applied to capture distinct strategic perspectives by purposefully selecting experts from both the corporate sector and management consulting. This dual-perspective approach ensures that the developed artifact accommodates different analytical objectives and scopes:

**1. Corporate Perspective:** Experts from within organizations focus on optimizing their own company’s sustainability communication, mitigating individual greenwashing risks, and extracting direct, actionable insights for internal reputation management.

**2. Consulting Perspective:** Experts from the consulting sector operate across organizational boundaries. Their objective is to deliver strategic impact for diverse clients, establish cross-industry benchmarks, and analyze broader, market-wide sustainability discourses.

Integrating both viewpoints ensures that the resulting Design Requirements lead to a highly versatile and broadly applicable social media analytics artifact.

| Expert ID | Industry / Sector | Current Role | Years of Experience | Interview Duration |
| :--- | :--- | :--- | :--- | :--- |
| E1 | Manufacturing | Head of Corporate Sustainability | 7 | 45 min |
| E2 | Manufacturing | Sustainability Professional | 5 | 50 min |
| E3 | Consulting | Senior Consultant ESG Reporting | 3 | 25 min |
| E4 | Consulting | Manager ESG Reporting | 8 | 40 min |

**Interview Setup & Analysis:**
- *Location / Plattform:* Microsoft Teams Calls
- *Approach:* It was made sure, that the interviews were semi-structured and as open as possible, avoiding any direct DR mentioning (as already identified through the literature review (see above)) of the interviewer. This way, the risk of a confirmation bias (a simple "yes I find that also helpful") was reduced. So rather, the needs and requirements of the interviewees were identified via talking about specific real world pain points of the specific industry or use case. For details see the interview protocols attached. 
- *Documentation:* MS Teams internal transcribition functionality was used to document the interview outcomes. The Interviews were then translated to English as all interviewees were German natives
- *Analysis:* The translated transcripts were analyzed using qualitative content analysis (Mayring, 2014) to systematically extract capabilities and challenges and combine them with the results from the literature review.

*(Note: The interview guide is provided as a separate PDF file in this repository: [Interview Guideline](./Interview-Guideline.pdf)*

## 3. Design Requirements Details
### 3.1 Mapping Table
The following table demonstrates the chain of evidence, tracing each Design Requirement back to the identified literature and allocates the sustainability experts based on the interview results (see also 3.2).

| Design Requirement | Source: Literature | Source: Expert Interview |
| :--- | :--- | :--- |
| **DR1:** Ability to extract a large number of social media posts from the past until the present (via X) | (Grevy Gotfredsen, 2023)(Bisbee & Munger, 2025) | E1; E3; E4|
| **DR2:** Extension of generic keyword post extraction to collect sustainability domain-specific information | (Patuelli et al., 2021)(Park et al., 2022)(Alkhodair et al., 2018) | - |
| **DR3:** Classification of social media posts in TBL dimensions | (Morales-Hernandez et al., 2022)(Park et al., 2022)(Sokolov et al., 2021)(Tang et al., 2023) | E1; E2 |
| **DR4:** Consideration of Sentiment of user posts on TBL dimensions | (Arya et al., 2023)(Cao, 2023)(Kudalkar, 2023)(Manetti & Bellucci, 2016)(Nguyen, 2024) | - |
| **DR5:** Ability to analyse TBL dimensions over time | (Aalijah, 2025)(Domalewska, 2021)(Jha & Verma, 2022)(Liang et al., 2020)(Nicolas et al., 2024)(Park et al., 2022) | E1; E2 |
| **DR6:** Gap analysis between organisation & user narratives | (Oppong-Tawiah & Webster, 2023)(Dwivedi et al., 2023)(Jha & Verma, 2024) | E2 |
| **DR7:** Correlation of engagement metrics with TBL dimensions | (Aksoy et al., 2022)(Bahar, 2023)(Kim & Hara, 2024)(Russo et al., 2022) | - |
| **DR8:** Visualization of results | (Asiri & Aksoy, 2022)(Jemiard Mmasomwayera Sinkula, 2024)(Stieglitz et al., 2018) | E1; E2 |
| **DR9:** (Cross)-sector benchmarking | - | E1; E3; E4 |
| **DR10:** Comparison of CSR report content with social media content | - | E1; E2; E4 |

### 3.2 Expert Interview Design Requirement Quotes
The following tables provides an overview of the exact quotes from the interviewed experts that could be mapped to the Design Requirements above.
For a detailed analysis of each interview please refer to the respective interview protocol ([Interview Protocol Expert 1 (E1)](./Interview-protocol_expert_1.pdf)|[Interview Protocol Expert 2 (E2)](./Interview-protocol_expert_2.pdf)|[Interview Protocol Expert 3 (E3)](./Interview-protocol_expert_3.pdf)|[Interview Protocol Expert 4 (E4)](./Interview-protocol_expert_4.pdf))


<table>
  <thead>
    <tr>
      <th>Expert</th>
      <th>mapped DR</th>
      <th>Quote</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="6"><strong>E1</strong></td>
      <td>DR1</td>
      <td>"...Also, we usually only realize there is a problem when a topic is already blowing up. We don't see it building up over time. To really understand if a specific issue has been a problem for a while, we would desperately need the ability to extract a large number of social media posts over time..."</td>
    </tr>
    <tr>
      <td>DR3</td>
      <td>"...It would save us weeks of reading through comments if we had the capability for an automatic classification of social media posts in the different sustainability dimensions..."</td>
    </tr>
    <tr>
      <td>DR5</td>
      <td>"...It is important to continuously check whether we are actually in line with the general perception of sustainability trends and how those trends evolved,..."</td>
    </tr>
    <tr>
      <td>DR8</td>
      <td>"...If I open a tool, I need to instantly understand everything that is going on without having to read a manual. So, a simple dashboard is an absolute must-have for me..."</td>
    </tr>
    <tr>
      <td>DR9</td>
      <td>"...I'm also really interested in what others are doing and how they are performing... "</td>
    </tr>
    <tr>
      <td>DR10</td>
      <td>"...We spend so much time on those reports, and we need to know if the topics resonate..."</td>
    </tr>
    <tr>
      <td rowspan="5"><strong>E2</strong></td>
      <td>DR3</td>
      <td>"...So at the end of the day, to really understand the public perception, I still end up just manually scrolling through the comment sections with my coffee in the morning, which obviously takes forever...What we really need to make this data actually workable for my reporting is an automated classification and not just some generic topic clustering, which are quite off in a lot of cases..."</td>
    </tr>
    <tr>
      <td>DR5</td>
      <td>"...We need to continuously check if our internal roadmap is still in line with the general perception of sustainability trends. These things move so fast on social media...I need to see how those trends evolved over the last months ..."</td>
    </tr>
    <tr>
      <td>DR6</td>
      <td>"...But if people in the comments are actually completely ignoring the (anonymized product here) and instead discussing our supply chain issues in Asia, those generic tools completely miss it..."</td>
    </tr>
    <tr>
      <td>DR8</td>
      <td>"...if I could just see the trends at a glance, like through some sort of intuitive dashboard with heatmaps or graphs, where I can immediately spot which ESG topics are gaining traction..."</td>
    </tr>
      <tr>
      <td>DR10</td>
      <td>"...But once it's published as a PDF on our website, we just cross our fingers and hope it actually covers the topics people care about. Sometimes the social media team posts a snippet from my report, and the comments are just crickets, or people complain about something entirely different..."</td>
    </tr>
    <tr>
      <td rowspan="2"><strong>E3</strong></td>
      <td>DR1</td>
      <td>"...we need to know what the public has been saying over the last two or three years to identify long-term trends or recurring controversies. But getting our hands on that older, historical data is incredibly difficult and expensive with standard listening tools..."</td>
    </tr>
    <tr>
      <td>DR9</td>
      <td>"...Clients don't just want to know how they are doing in a vacuum; they want to know how they stack up against the rest of the market..."</td>
    </tr>
    <tr>
      <td rowspan="3"><strong>E4</strong></td>
      <td>DR1</td>
      <td>"...I need to be able to pull a massive archive of data that goes back years, not just weeks, to really get the big picture..."</td>
    </tr>
    <tr>
      <td>DR9</td>
      <td>"...I need the ability to instantly see how my client is performing relative to the rest of the industry or their direct DAX competitors..."</td>
    </tr>
    <tr>
      <td>DR10</td>
      <td>"...It's almost impossible right now to systematically map what’s written in the official report against what the public is actually shouting about online..."</td>
  </tbody>
</table>


## 4. References

