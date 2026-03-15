# Online Appendix: Sustainalyzer (ECIS 2026 Submission)

This repository contains the supplementary methodological details for the paper "Sustainalyzer – An Analysis Tool for Sustainability Communication on Social Media", addressing the space limitations of the conference format.
Concretely, the following details are adressed:

* [1. Systematic Literature Review Overview](#1-systematic-literature-review-overview)
* [2. Expert Interviews Overview](#2-expert-interviews-overview)
* [3. Design Requirements Mapping Table](#3-design-requirements-mapping-table)
* [4. Tool Provider Interviews](#4-tool-provider-interviews)
* [5. References](#5-references)
  

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
| Inclusion/Exclustion Criteria | Only peer-reviewed journal and conference papers in English |


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

**Interview Setup:**
- *Location / Plattform:* Microsoft Teams Calls
- *Approach:* It was made sure, that the interviews were semi-structured and as open as possible, avoiding any direct DR mentioning (already identified through the literature review (see above)) of the Interviewer. This way, the risk of a simple "yes I find that also helpful" was reduced. So rather, the needs and requirements of the interviewees were identified via talking about specific real world pain points. For details see the interview protocols attached. 
- *Documentation:* MS Teams internal transcribition functionality was used to document the interview outcomes 

*(Note: The full, anonymized interview guide is provided as a separate PDF file in this repository: LINK)*

## 3. Design Requirements Details
### 3.1 Mapping Table
The following table demonstrates the chain of evidence, tracing each Design Requirement back to the identified literature and alocates the sustainability experts based on the interview results (see also 3.2).

| Design Requirement | Source: Literature | Source: Expert Interview |
| :--- | :--- | :--- |
| **DR1:** Ability to extract a large number of social media posts from the past until the present (via X) | (Grevy Gotfredsen, 2023)(Bisbee & Munger, 2025) | E1; E3; E4|
| **DR2:** Extension of generic keyword post extraction to collect sustainability domain-specific information | (Patuelli et al., 2021)(Park et al., 2022)(Alkhodair et al., 2018) | - |
| **DR3:** Classification of social media posts in TBL dimensions | (Morales-Hernandez et al., 2022; Park et al., 2022; Sokolov et al., 2021)(Al-Garadi et al., 2021; Tang et al., 2023) | E1; E2 |
| **DR4:** Consideration of Sentiment of user posts on TBL dimensions | (Manetti & Bellucci, 2016)(Arya et al., 2023; Cao, 2023; Nguyen, 2024) | - |
| **DR5:** Ability to analyse TBL dimensions over time | (Chae & Park, 2018)(Park et al., 2022)(Liang et al., 2020)(Nicolas et al., 2024)(Aalijah, 2025)(Domalewska, 2021)(Jha & Verma, 2022); expert interviews | - |
| **DR6:** Gap analysis between organisation & user narratives | (Chung et al., 2020; Dwivedi et al., 2023; Jha & Verma, 2024; Mukherjee, 2020; Oppong-Tawiah & Webster, 2023; Schivinski et al., 2016) | E2 |
| **DR7:** Correlation of engagement metrics with TBL dimensions | (Aksoy et al., 2022; Bahar, 2023; Kim & Hara, 2024; Russo et al., 2022) | - |
| **DR8:** Visualization of results | (Asiri & Aksoy, 2022; Jemiard Mmasomwayera Sinkula, 2024; Stieglitz et al., 2018) | *E1; E2 |
| **DR9:** (Cross)-sector benchmarking | - | E1; E3; E4 |
| **DR10:** Comparison of CSR report content with social media content | - | E1; E2; E4 |

### 3.2 Expert Interview Design Requirement Quotes
The following tables provides an overview of the exact quotes from the interviewed experts that could be mapped to the Design Requirements above.
For a detailed analysis of each interview please refer to the respective interview protocal (LINK | LINK | LINK | LINK)


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
      <td rowspan="4"><strong>E1</strong></td>
      <td>DR1</td>
      <td>"...</td>
    </tr>
    <tr>
      <td>DR3</td>
      <td>"..."</td>
    </tr>
    <tr>
      <td>DR8</td>
      <td>"..."</td>
    </tr>
    <tr>
      <td>DR10</td>
      <td>"..."</td>
    </tr>
    <tr>
      <td rowspan="4"><strong>E2</strong></td>
      <td>DR3</td>
      <td>"..."</td>
    </tr>
    <tr>
      <td>DR6</td>
      <td>"..."</td>
    </tr>
    <tr>
      <td>DR8</td>
      <td>"..."</td>
    </tr>
      <tr>
      <td>DR10</td>
      <td>"..."</td>
    </tr>
    <tr>
      <td rowspan="2"><strong>E3</strong></td>
      <td>DR1</td>
      <td>"..."</td>
    </tr>
    <tr>
      <td>DR9</td>
      <td>"..."</td>
    </tr>
    <tr>
      <td rowspan="3"><strong>E4</strong></td>
      <td>DR1</td>
      <td>"..."</td>
    </tr>
    <tr>
      <td>DR9</td>
      <td>"..."</td>
    </tr>
    <tr>
      <td>DR10</td>
      <td>"..."</td>
  </tbody>
</table>

## 4. Tool-Provider Interviews
To enhance the transparency of the tool provider comparison, the results of the conducted interviews can be found here.

## 5. References

