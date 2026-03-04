# Web Research Skill

**Version:** 1.0.0  
**Category:** Research & Analysis  
**Required Capabilities:** `web_search`, `web_fetch`

---

## Overview

This skill teaches you how to conduct structured, credible web research that produces actionable insights with proper source attribution. You'll learn to transform vague questions into targeted searches, evaluate source quality, synthesize findings, and deliver results in a standardized format that enables decision-making.

**Core principle:** Research is not search. Search finds pages; research builds understanding.

---

## The Research Workflow

Every research task follows this four-stage process:

### 1. **Query Decomposition** → Break down the question
### 2. **Search & Fetch** → Find and extract information
### 3. **Source Evaluation** → Assess credibility and relevance
### 4. **Synthesis & Reporting** → Integrate findings into structured output

Let's break down each stage.

---

## Stage 1: Query Decomposition

### The Problem
Users rarely ask research questions in searchable form. 

**User:** "Is Company X a good investment?"  
**Not searchable** — too vague, subjective, time-dependent.

Your job: translate intent into specific, answerable sub-queries.

### Decomposition Framework

Ask yourself:
1. **What type of answer does this need?** (Factual, comparative, evaluative, procedural)
2. **What specific information would answer this?** (Numbers, dates, expert opinions, examples)
3. **What's the time scope?** (Current, historical, trending)
4. **What context is missing?** (Domain, geography, use case)

### Example: Breaking Down a Vague Question

**Original:** "Is Company X a good investment?"

**Decomposed queries:**
```
1. "Company X financial performance 2024 revenue profit"
   → Need: Recent financial data

2. "Company X news scandals lawsuits 2024"
   → Need: Risk factors

3. "Company X competitors market share comparison"
   → Need: Competitive position

4. "Company X stock analyst ratings price target"
   → Need: Expert opinions

5. "Company X industry trends outlook 2025"
   → Need: Market context
```

**Why this works:** Each query is:
- **Specific** — targets a single aspect
- **Searchable** — uses terms that appear in real documents
- **Answerable** — can be satisfied with facts, not opinions
- **Time-bound** — includes temporal markers when relevant

### Query Patterns by Research Type

| Research Type | Query Pattern | Example |
|---------------|---------------|---------|
| **Factual** | `[entity] [attribute] [timeframe]` | "Tesla revenue Q4 2024" |
| **Comparative** | `[A] vs [B] [dimension]` | "React vs Vue performance 2024" |
| **Procedural** | `how to [action] [constraint]` | "how to deploy Next.js on Cloudflare" |
| **Evaluative** | `[entity] review rating comparison` | "Claude 4 vs GPT-4 benchmark comparison" |
| **Trend** | `[topic] trend forecast [year]` | "AI agent adoption trends 2025" |

### Bad vs Good Queries

| ❌ Bad | ✅ Good | Why? |
|--------|---------|------|
| "best practices" | "React server components best practices 2024" | Added tech, year |
| "market size" | "AI coding assistant market size revenue 2024" | Added specifics |
| "how does it work" | "how does transformer attention mechanism work" | Clear subject |
| "pros and cons" | "Next.js App Router advantages disadvantages vs Pages Router" | Explicit comparison |

### Decomposition Checklist

Before searching, verify:
- [ ] Each query is a complete, searchable phrase
- [ ] No pronouns (replace "it", "they" with actual entities)
- [ ] Temporal context specified when relevant
- [ ] Domain/geography specified when relevant
- [ ] Technical level appropriate (don't use jargon if searching consumer info)

---

## Stage 2: Search & Fetch Workflow

### The Two-Step Process

**Search** = finding promising sources  
**Fetch** = extracting content from those sources

### Search Strategy

#### 1. Start Broad, Then Narrow
```
First search:  "AI code generation tools"
Second search: "AI code generation accuracy comparison Copilot Cursor"
Third search:  "GitHub Copilot vs Cursor IDE performance benchmarks 2024"
```

Why: You don't know what vocabulary the best sources use until you see some results.

#### 2. Use Multiple Query Variants

For "How accurate is weather forecasting?":
```
- "weather forecast accuracy percentage"
- "how accurate are weather predictions"
- "meteorology forecast reliability studies"
- "weather model accuracy comparison NOAA"
```

Why: Different sources use different terminology. Trying multiple phrasings finds more angles.

#### 3. Look for Primary Sources

**Tiers of source quality:**
```
Tier 1: Primary research, official data, documentation
  → Academic papers, company reports, technical docs, government data

Tier 2: Expert analysis, industry publications
  → Analyst reports, technical blogs by practitioners, trade journals

Tier 3: News and aggregators
  → News articles, Wikipedia, general blogs

Tier 4: Opinion and unverified
  → Social media, forums, uncited claims
```

**Search strategies by tier:**
- Tier 1: Add "filetype:pdf", "study", "research", "documentation"
- Tier 2: Add site filters like "site:*.edu", "site:github.com"
- Tier 3: Standard searches, news filters
- Tier 4: Avoid unless checking sentiment or anecdotes

#### 4. Time-Bound Searches

For time-sensitive topics:
- Add year: "Kubernetes best practices 2024"
- Use freshness filters when available
- Check publication dates after fetching

For historical research:
- Add specific years: "Tesla Model S reviews 2012"
- Search for "history", "evolution", "timeline"

### Fetch Strategy

#### When to Fetch
✅ **Fetch if:**
- Title/snippet indicates direct answer to your query
- Source appears credible (known domain, publication, institution)
- You need specific details (numbers, quotes, examples)
- Multiple search results reference this source

❌ **Skip if:**
- Title is clickbait ("You won't believe...")
- Content is likely behind paywall (unless critical)
- Source is obviously low-quality (spam site, content farm)
- Snippet already contains the full answer

#### How to Fetch Efficiently

**Extract what you need:**
```
1. Headline + key facts → Quick scan for relevance
2. Numbers, dates, quotes → Specific data points
3. Author, publication date → Source quality signals
4. Citations/references → Paths to better sources
```

**Don't:**
- Read every word
- Fetch tangentially related pages
- Get distracted by interesting but irrelevant content
- Follow every link

#### Handling Paywalls and Access Limits

**Strategies:**
1. Check if there's a free PDF version (academic papers)
2. Search for the title + "PDF" or "full text"
3. Look for author's personal site (often hosts their papers)
4. Check if abstract/summary provides enough info
5. Find reporting or analysis that cites the paywalled source
6. For critical sources: note the limitation and suggest user access if needed

### Fetch Output Format

For each fetched page, note:
```
URL: [full URL]
Title: [page title]
Date: [publication date or "Accessed: YYYY-MM-DD" if no date]
Key Info: [bullet points of relevant facts extracted]
Quality: [Tier 1-4 rating]
```

### Search & Fetch Limits

**When to stop searching:**
- ✅ You have 3-5 high-quality sources that agree on core facts
- ✅ You've found quantitative data from credible sources
- ✅ Additional searches return duplicate/similar sources
- ✅ You've covered multiple perspectives (if topic is debated)

**When to search more:**
- ❌ Sources conflict on key facts (need tie-breaker sources)
- ❌ Only found Tier 3-4 sources (need better quality)
- ❌ Found only recent info but need historical context
- ❌ Topic has multiple dimensions and you've only covered one

---

## Stage 3: Source Evaluation

### Credibility Framework

Not all web content is equally reliable. Use this framework to assess sources.

### The CRAAP Test (Modified for Web Research)

#### **C — Currency**
- When was this published/updated?
- Is the information time-sensitive?
- Are there more recent sources?

**Red flags:**
- No publication date visible
- Information obviously outdated (dead links, old product versions)
- Claiming "current" statistics from years ago

#### **R — Relevance**
- Does this directly address your query?
- Is the detail level appropriate (too basic vs too technical)?
- Is this the right domain/geography?

**Red flags:**
- Title matches but content doesn't deliver
- Mixing related but distinct topics
- Geographic mismatch (UK data when you need US)

#### **A — Authority**
- Who wrote this? What are their credentials?
- Who published this? (Institution, company, publication)
- Is the author identifiable and verifiable?

**Red flags:**
- No author listed (except for institutional pages like docs)
- Author has no relevant expertise
- Site has no "About" page or clear ownership

#### **A — Accuracy**
- Are claims backed by evidence?
- Are sources cited?
- Can you verify key facts elsewhere?
- Is the writing quality high (grammar, structure)?

**Red flags:**
- No citations for factual claims
- Claims that contradict multiple other sources
- Obvious factual errors
- Poor writing quality (often indicates content farm)

#### **P — Purpose**
- Why does this content exist?
- Is it educational, commercial, opinion, advocacy?
- Are biases disclosed?

**Red flags:**
- Heavy commercial bias (only praising products they sell)
- Extreme advocacy without acknowledging counterpoints
- Designed to drive affiliate sales
- Sensationalist language ("everything you know is wrong")

### Source Tier Checklist

**Tier 1: Authoritative** ⭐⭐⭐⭐⭐
- [ ] Primary research or official documentation
- [ ] Clear author credentials
- [ ] Peer-reviewed or editorially reviewed
- [ ] Citations provided
- [ ] No obvious commercial bias
- [ ] Recent or explicitly historical

**Examples:** Academic papers, technical documentation, government data, company financial reports, official specifications

**Tier 2: Expert** ⭐⭐⭐⭐
- [ ] Written by domain expert
- [ ] Published by reputable outlet
- [ ] Evidence-based claims
- [ ] Sources cited or verifiable
- [ ] Transparent about limitations

**Examples:** Established tech blogs (Ars Technica, The Verge for tech), industry analyst reports, expert practitioner blogs, trade publications

**Tier 3: General** ⭐⭐⭐
- [ ] Mainstream news or general publication
- [ ] Facts generally checkable
- [ ] No obvious red flags
- [ ] Useful for context/summaries
- [ ] Should be corroborated with higher-tier sources

**Examples:** News articles, Wikipedia, general blogs, press releases

**Tier 4: Questionable** ⭐⭐
- [ ] Useful only for sentiment/opinion research
- [ ] Cannot be primary source for facts
- [ ] Uncited claims
- [ ] Unknown author/publisher
- [ ] Potential bias not disclosed

**Examples:** Forum posts, social media, anonymous blogs, content farms, AI-generated content farms

**Tier 5: Unreliable** ⭐
- [ ] Do not use
- [ ] Misinformation, conspiracy theories
- [ ] Completely uncited
- [ ] Contradicts all credible sources

### Conflict Resolution

When sources disagree:

1. **Check the tiers** — Tier 1 beats Tier 3
2. **Check the dates** — More recent usually better (unless historical topic)
3. **Check the specificity** — Detailed beats vague
4. **Look for consensus** — 4 sources agree, 1 disagrees → go with majority
5. **Check primary vs secondary** — Original research beats reporting on research
6. **Find a third source** — Break the tie

### Special Cases

#### Wikipedia
- **✅ Good for:** Overview, terminology, finding primary sources (check citations)
- **❌ Not good for:** Final source, controversial topics, specific facts
- **Strategy:** Read Wikipedia → follow citations to primary sources

#### Social Media
- **✅ Good for:** Real-time breaking news, sentiment, user experiences
- **❌ Not good for:** Facts, statistics, authoritative info
- **Strategy:** Treat as leads to verify elsewhere

#### Press Releases
- **✅ Good for:** Company announcements, official positions
- **❌ Not good for:** Critical analysis, unbiased assessment
- **Strategy:** Use for official data, supplement with external analysis

#### AI-Generated Content
- **Growing problem:** Many sites now publish AI-generated articles
- **Detection signals:** Generic writing, no author bio, recent domain, excessive ads
- **Strategy:** Verify facts in multiple non-AI sources

---

## Stage 4: Synthesis & Reporting

### The Research Report Format

Every research output should follow this structure:

```markdown
# Research Report: [Topic]

**Query:** [Original question]  
**Conducted:** [Date]  
**Confidence Level:** [High/Medium/Low]

---

## Executive Summary
[2-3 sentences: What was asked, what you found, key takeaway]

---

## Query Breakdown
**Primary question:** [Main question]  

**Sub-queries investigated:**
1. [Query 1]
2. [Query 2]
3. [Query 3]

---

## Sources

### Primary Sources
1. **[Source Title]**
   - URL: [link]
   - Author: [name/organization]
   - Date: [publication date]
   - Tier: [1-5]
   - Summary: [1-2 sentences on what this source provided]

2. [Additional sources...]

### Supporting Sources
[Secondary sources that corroborated findings]

---

## Findings

### [Topic Area 1]
[Detailed findings with inline citations]

Key points:
- [Fact 1] [Source ref]
- [Fact 2] [Source ref]
- [Fact 3] [Source ref]

### [Topic Area 2]
[Continue for each major area]

---

## Key Takeaways

1. **[Takeaway 1]**
   [One clear, actionable insight]

2. **[Takeaway 2]**
   [Another clear, actionable insight]

3. **[Takeaway 3]**
   [Final clear, actionable insight]

---

## Limitations & Uncertainties

- [What couldn't be definitively answered]
- [Where sources conflicted]
- [What would require deeper research]
- [Time-sensitive info that may become outdated]

---

## Confidence Assessment

**Overall: [High/Medium/Low]**

- **Source Quality:** [Assessment of source tiers used]
- **Consensus:** [Level of agreement across sources]
- **Completeness:** [How fully the query was answered]
- **Currency:** [How up-to-date the information is]

---

## Recommended Follow-Up

[If applicable: what additional research would strengthen findings]
```

### Writing Guidelines

#### Executive Summary
- Lead with the answer, not the process
- ❌ "I searched multiple sources and found that..."
- ✅ "X is true because A, B, and C."

#### Findings Section
- Organize by theme, not by source
- Use sub-headers for scannability
- Cite inline: "Revenue grew 23% in Q4 [Source: Tesla Q4 Report]"
- Lead with facts, not opinions
- Quantify when possible: "majority of sources" → "4 out of 5 sources"

#### Key Takeaways
- Make them actionable
- ❌ "There is a lot of information about X"
- ✅ "X is the preferred approach because of Y constraint"
- Prioritize: most important first
- Keep to 3-5 takeaways (more = diluted impact)

#### Confidence Level Guide

**High Confidence** ✅
- Multiple Tier 1-2 sources agree
- Recent, primary data
- No significant conflicts
- Topic is well-documented

**Medium Confidence** ⚠️
- Mostly Tier 2-3 sources
- Some minor conflicts resolved
- Limited primary sources
- Topic is somewhat ambiguous

**Low Confidence** ⚠️⚠️
- Tier 3-4 sources only
- Significant conflicts unresolved
- Outdated information
- Topic lacks good documentation
- Recommend further research before action

### Citation Formats

#### In-Text Citations
```markdown
"The global AI market is projected to reach $407 billion by 2027 [Fortune Business Insights, 2024]."
```

#### Source List Format
```markdown
**Title of Source** (Author/Org, Date)
URL: [full URL]
Accessed: [date]
Type: [Report/Article/Documentation]
```

#### Handling Undated Content
```markdown
**Title of Source** (Author/Org)
URL: [full URL]
Accessed: 2024-03-04
Note: No publication date listed
```

---

## Deep Research vs Quick Lookups

### When to Do Quick Research (15-30 min)

**Characteristics:**
- Simple factual question
- Well-documented topic
- Low stakes (informational, not decision-critical)
- Broad answer acceptable

**Approach:**
- 2-3 queries
- 3-5 sources
- Tier 2-3 acceptable
- Brief report (< 500 words)

**Example:** "What's the current version of Next.js and what are the key features?"

### When to Do Deep Research (1-3 hours)

**Characteristics:**
- Complex, multi-faceted question
- High stakes (financial, strategic decisions)
- Conflicting information in landscape
- Requires analysis, not just facts

**Approach:**
- 5-10+ queries
- 10-15 sources
- Prioritize Tier 1-2
- Full structured report
- Cross-verify all key claims

**Example:** "Should we migrate our infrastructure from AWS to Google Cloud?"

### Escalation Signals

Start quick, escalate to deep if:
- ❌ Can't find credible sources in first few searches
- ❌ Top sources significantly conflict
- ❌ User's follow-up questions reveal higher stakes
- ❌ Topic is more complex than initially apparent
- ❌ Initial findings suggest the wrong question was asked

---

## Handling Special Scenarios

### Scenario: No Good Sources Exist

**What to do:**
1. Report the absence of quality sources
2. Explain what you searched for
3. Provide best available with heavy caveats
4. Suggest alternative approaches (expert consultation, original research)

**Example:**
```
I searched for quantitative data on [topic] using queries X, Y, Z.
No Tier 1-2 sources found. This suggests the topic is either:
- Too niche for public research
- Too new for published studies
- Proprietary/confidential

Best available: [Tier 3 sources] but treat as anecdotal.
Recommendation: Consider [expert interviews / original survey / etc.]
```

### Scenario: Topic Is Controversial or Politicized

**What to do:**
1. Acknowledge the controversy explicitly
2. Represent multiple perspectives
3. Distinguish facts from interpretation
4. Be transparent about source biases
5. Focus on areas of consensus if any

**Example structure:**
```
## Positions on [Topic]

### Perspective A (Sources: X, Y)
[Claims and evidence]

### Perspective B (Sources: Z, W)
[Claims and evidence]

### Areas of Agreement
[What both sides accept as fact]

### Key Disputes
[Where they disagree and why]
```

### Scenario: Sources Conflict on Key Facts

**What to do:**
1. Don't hide the conflict
2. Present both claims
3. Evaluate which is more credible
4. Note your reasoning

**Example:**
```
**Conflict:** Revenue figures for Q4

- Source A (Company SEC Filing, 2024): $42.3M
- Source B (TechNews article, 2024): $45M

**Resolution:** Using Source A. SEC filings are primary sources (Tier 1) 
while the news article (Tier 3) may have used preliminary estimates.
```

### Scenario: Information Is Rapidly Changing

**What to do:**
1. Note the date of research prominently
2. Flag time-sensitive nature
3. Provide as of dates for specific claims
4. Suggest a refresh timeline

**Example:**
```
⚠️ **Note:** Cryptocurrency prices and AI model capabilities change rapidly. 
This research reflects information as of March 4, 2024. 
Recommend refreshing if using after [date + 1 week].
```

### Scenario: User Asks Unanswerable Question

**What to do:**
1. Clarify why it's unanswerable
2. Offer related answerable questions
3. Suggest what would be needed to answer it

**Example:**
```
**Query:** "Will Bitcoin hit $100k in 2024?"

**Issue:** This asks for a prediction of inherently unpredictable future events.

**What I can research instead:**
- Historical Bitcoin price patterns
- Expert price predictions (with track records)
- Factors analysts cite as bullish/bearish
- Comparison to past prediction accuracy

Would you like me to research one of these angles?
```

---

## Quality Checklist

Before delivering research, verify:

### Content Quality
- [ ] Original question is clearly answered
- [ ] All key claims are sourced
- [ ] Sources are credible (majority Tier 1-2 for high-stakes research)
- [ ] Conflicts are identified and resolved
- [ ] Limitations are acknowledged
- [ ] Confidence level is justified

### Structure Quality
- [ ] Executive summary is clear and front-loaded
- [ ] Findings are organized by theme
- [ ] Sources are documented with full URLs and dates
- [ ] Key takeaways are actionable
- [ ] Report is scannable (headers, bullets, bold for key facts)

### Intellectual Honesty
- [ ] Didn't cherry-pick sources to support a predetermined conclusion
- [ ] Represented counterpoints if they exist
- [ ] Acknowledged uncertainty where present
- [ ] Didn't overstate confidence
- [ ] Distinguished facts from interpretation

---

## Anti-Patterns to Avoid

### ❌ Search Engine Optimization
**Bad:** Treating the first Google result as the answer  
**Why:** SEO ≠ quality. First result optimizes for clicks, not accuracy.  
**Fix:** Evaluate sources, don't just trust ranking.

### ❌ Confirmation Bias
**Bad:** Only citing sources that agree with your initial hunch  
**Why:** Produces misleading research that misses important counterpoints.  
**Fix:** Actively search for counter-evidence. If you don't find it, note that.

### ❌ Link Hoarding
**Bad:** Fetching 20 pages and dumping URLs in a list  
**Why:** That's not research, that's outsourcing the work to the user.  
**Fix:** Synthesize. Extract key points. Tell a coherent story.

### ❌ Wikipedia Verbatim
**Bad:** Copying Wikipedia summary as your findings  
**Why:** Wikipedia is a starting point, not an end point.  
**Fix:** Use Wikipedia to find primary sources, then cite those.

### ❌ Recency Bias
**Bad:** Only citing sources from the past month  
**Why:** Misses established knowledge, historical context.  
**Fix:** Mix recent and foundational sources. Check if "new" findings contradict established facts.

### ❌ Appeal to Authority Without Verification
**Bad:** "Expert X says Y, so it's true"  
**Why:** Even experts are wrong sometimes, especially outside their domain.  
**Fix:** Check if other experts agree. Look for evidence behind the claim.

### ❌ False Balance
**Bad:** Giving equal weight to fringe and mainstream positions  
**Why:** "Some say Earth is round, some say flat" is misleading.  
**Fix:** Reflect actual consensus. Note when a position is fringe/minority.

### ❌ Zombie Statistics
**Bad:** Citing stats without checking their origin  
**Why:** Many "statistics" are misquoted, outdated, or fabricated.  
**Fix:** Trace stats to primary sources. Verify dates. Check methodology.

---

## Advanced Techniques

### Lateral Reading
When evaluating a source, don't just read it deeply—read around it:
1. Open new tabs for author, publication, cited sources
2. Search for: "[author name] credibility", "[site name] reliability"
3. Check if other credible sites cite/link to this source
4. Look for critical commentary or fact-checks

### Triangulation
For critical facts, verify across three independent sources:
- Different authors
- Different publication types (e.g., news + academic + official)
- Different methodologies (if research-based)

If you can't triangulate, flag the claim as unverified.

### Reverse Image Search
For research involving images, charts, or infographics:
- Verify the source wasn't stolen or manipulated
- Find higher-quality versions
- Discover the original context

### Domain Expertise Recognition
Learn to recognize authoritative domains by field:
- **Tech:** ArsTechnica, IEEE, ACM, GitHub engineering blogs
- **Science:** Nature, Science, PLOS, university press releases
- **Business:** HBR, WSJ, Financial Times, McKinsey, BCG
- **Policy:** Brookings, RAND, Pew Research, official .gov sites

### The 10-Year Rule
For established fields, find foundational sources from ~10 years ago:
- Reveals what's truly settled vs what's hype
- Shows which "revolutionary" ideas actually stuck
- Provides historical context

---

## Continuous Improvement

### After Each Research Task, Reflect:

1. **Did I answer the actual question?**
   - Or did I answer the question I wished they'd asked?

2. **Could someone act on this?**
   - Or is it a data dump without insights?

3. **Would I bet money on these findings?**
   - If not, what would increase confidence?

4. **Did I waste time on low-value sources?**
   - What signals should I watch for next time?

5. **Was my confidence level calibrated?**
   - If they fact-checked me, would I be right?

### Red Flags You're Doing It Wrong

- 🚩 You spent an hour reading but don't have concrete facts
- 🚩 You can't explain why one source is better than another
- 🚩 Your report is mostly URLs and block quotes
- 🚩 You found exactly what you expected to find (suspiciously convenient)
- 🚩 You can't articulate what would change your conclusion
- 🚩 Your findings sound like marketing copy

### Signs You're Doing It Right

- ✅ You can summarize findings without looking at notes
- ✅ You found something that surprised you
- ✅ You can explain trade-offs and limitations
- ✅ Someone could fact-check your work and verify it
- ✅ Your confidence level matches the evidence
- ✅ A domain expert would call this "useful" not "wrong"

---

## Remember

**Research is not about being right—it's about being useful.**

A good research report:
- Answers the question (or clarifies why it can't be answered)
- Provides decision-relevant insights
- Acknowledges limitations
- Is transparent about sources and confidence
- Can be verified by the reader

**You are not the source of truth. You are the curator of sources.**

Your value is in:
1. Finding better sources than the user would find alone
2. Evaluating credibility
3. Synthesizing across sources
4. Identifying patterns and conflicts
5. Presenting insights clearly

Do this well, and you become an indispensable research partner.

---

## Quick Reference Card

### Research Process
1. **Decompose** → Break vague question into specific queries
2. **Search** → Multiple query variants, prioritize quality signals
3. **Fetch** → Extract key info, note source details
4. **Evaluate** → CRAAP test, tier classification
5. **Synthesize** → Organize by theme, cite sources, write clearly
6. **Report** → Structured format with confidence level

### Source Tiers
- **Tier 1:** Primary research, official docs (⭐⭐⭐⭐⭐)
- **Tier 2:** Expert analysis, industry pubs (⭐⭐⭐⭐)
- **Tier 3:** News, general sources (⭐⭐⭐)
- **Tier 4:** Opinion, unverified (⭐⭐)
- **Tier 5:** Unreliable (⭐)

### When to Stop Searching
✅ 3-5 quality sources agree  
✅ Found quantitative data from credible sources  
✅ Covered multiple perspectives  
✅ Additional searches return duplicates  

### Red Flags
🚩 No author or date  
🚩 No sources cited  
🚩 Contradicts all other sources  
🚩 Clickbait title  
🚩 Poor writing quality  
🚩 Heavy commercial bias  

### Confidence Levels
- **High:** Multiple Tier 1-2, recent, consensus
- **Medium:** Tier 2-3, minor conflicts, decent coverage
- **Low:** Tier 3-4 only, major conflicts, outdated, gaps

---

**End of Skill**
