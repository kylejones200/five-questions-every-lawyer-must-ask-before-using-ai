# Five Questions Every Lawyer Must Ask Before Using AI A simple framework for determining whether --- and how --- to use AI for
any legal task.

::::### Five Questions Every Lawyer Must Ask Before Using AI 

#### *A simple framework for determining whether --- and how --- to use AI for any legal task.*
You're staring at a stack of contracts that need review by end of week.
Your colleague mentions she used AI to speed up similar work. You're
tempted.

But you've heard the horror stories: Steven Schwartz citing fake cases
in federal court. Michael Cohen's attorney relying on fabricated
citations from Google Bard. Courts issuing sanctions. Bar associations
issuing warnings.

The question isn't whether AI can help --- it clearly can. The question
is: when should you use it, and how do you use it safely?


Here's a simple framework. Before using AI for any legal task, ask
yourself five questions. If you can answer all five confidently,
proceed. If you can't, stop.

### Question 1: Is This Confidential Client Information?
This is the threshold question. Get it wrong and you may violate ABA
Model Rule 1.6, waive attorney-client privilege, or expose client
information to third parties.

The Rule: ABA Model Rule 1.6 states: "A lawyer shall not reveal
information relating to the representation of a client unless the client
gives informed consent."

This duty applies to all client information, whether or not it's
privileged in the evidentiary sense.

The Problem: When you input text into a public AI system like ChatGPT
(free version), Claude (free version), or Gemini, you disclose
information to the AI vendor, potentially expose information if the
vendor is hacked or subpoenaed, may allow the vendor to use it for
training future models, and lose control if the vendor's policies
change. Each of these scenarios creates potential confidentiality
violations.

Italy's data protection authority illustrated this risk dramatically.
They asked OpenAI: "What do you do with the personal information of
Italian citizens?" OpenAI couldn't answer the question adequately. Italy
temporarily suspended ChatGPT.

Alexander Andhov, a legal technology scholar, identifies the fundamental
issue: "If I'm a lawyer and I'm using \[AI tools\] and I'm actually
using some form of my own protective data that I wouldn't want
necessarily to be shared with general public... what happens with your
data?"

The Framework:

Use public or free AI tools only if the information is already
public --- such as published court opinions --- or you've redacted all
confidential information, or the client has given informed consent after
being advised of the risks. Reserve enterprise AI tools like OpenAI API
with BAA, Azure OpenAI, or Claude for Enterprise for situations where
the vendor provides a Business Associate Agreement or equivalent data
protection contract, commits that data won't be used for training,
offers access controls and audit logging, and you've verified the
vendor's security measures meet your requirements. Deploy private or
on-premises AI for highly sensitive matters involving government
clients, trade secrets, or matters under seal, situations where even
enterprise tools present unacceptable risk, or clients who specifically
prohibit cloud-based AI.

The Action: Before inputting anything into AI, ask: "Is this
confidential?" If yes, verify your tool has appropriate data protection.
If you can't verify that, don't proceed.

### Question 2: Am I Asking AI to Generate Legal Citations or Verify Legal Authority?
This is where the Mata v. Avianca and Michael Cohen cases went wrong.

The Problem: AI language models generate text that looks like legal
citations based on patterns in their training data. They don't search
databases. They predict what a citation should look like.

Professor Piek Vossen of VU University Amsterdam explains: "It's a
generative language model that has seen massive examples of text and
from this it builds up an expectation after seeing a sequence of words
what would be the next word... in this way it basically generates an
answer or a story."

The model predicts what a citation *should look like*. It doesn't verify
whether it *actually exists*.

Asking AI to verify its own output doesn't solve this. Michael Cohen
learned this when Google Bard confirmed that fabricated citations were
real. They weren't. AI models generate confident-sounding responses
regardless of accuracy.

The Framework:

Never ask AI to generate case citations for you to cite in a brief,
confirm whether a case exists, verify whether a statute has been
amended, or quote language from a case without you checking the actual
opinion. Always use AI only for identifying potential search terms or
legal issues to research, summarizing cases that you've already verified
exist and are relevant, organizing research results after you've
independently verified the underlying sources, or drafting research
memos that include your own verification of all citations.

The Action: Every case citation must be verified in Westlaw, Lexis, or
another authoritative legal database. Every quoted passage must be
checked against the actual opinion. Every Shepard's or KeyCite signal
must be confirmed. No exceptions.

### Question 3: Can I Verify the AI's Output Against Source Documents?
The difference between useful AI and dangerous AI often comes down to
one factor: can you verify the output?

The Framework:

High-confidence tasks involve verifiable AI output. Document
summarization works well: AI reads a 200-page contract and summarizes
key terms, which you can verify by checking against the actual contract.
Document comparison proves reliable when AI identifies differences
between two versions of an agreement and you review the flagged
sections. Clause extraction succeeds when AI pulls all force majeure
clauses from 50 contracts and you spot-check the results. Issue flagging
serves its purpose when AI reviews contracts and flags provisions that
deviate from your standard language, allowing you to determine whether
flagged items are actually problematic.

Low-confidence tasks involve output that's difficult to verify. Legal
strategy suggestions raise questions: when AI recommends arguments or
approaches, how do you know if they're optimal? You're relying on AI's
judgment rather than your own. Novel legal analysis creates similar
problems: when AI identifies a potential legal theory, determining
whether it's sound and whether courts have actually accepted this
argument requires extensive additional research. Risk assessments prove
particularly treacherous: when AI rates litigation risk as "moderate,"
what's that based on? The assessment itself requires judgment you can't
easily verify.

The Action: If you can't verify the AI's output against source documents
or independent evidence, don't rely on it for client advice or court
submissions.

### Question 4: Could Bias in the AI's Training Data Affect the Output?
AI models are trained on historical data. If that data reflects societal
biases, the AI will too.

The Problem: Studies have found that AI systems can produce biased
outputs in sentencing recommendations reflecting racial disparities,
credit decisions showing gender and race disparities, employment
screening exhibiting gender and disability bias, and risk assessments
displaying socioeconomic bias. Even in document review, AI trained
primarily on large-firm commercial contracts might perform poorly on
consumer agreements or employment contracts.

The Framework:

Lower-risk applications include comparing contracts to identify
differences --- an objective task --- extracting specific data points
like dates, parties, and amounts, organizing documents by type or topic,
and summarizing factual content with verification. Higher-risk
applications include predicting litigation outcomes that may reflect
biases in historical case outcomes, assessing witness credibility in
ways that may reflect implicit biases, evaluating employment candidates
where known bias issues exist, and determining creditworthiness or risk
scores.

The Action:

For higher-risk applications, understand how the AI was trained and
tested for bias. Validate outputs against diverse datasets. Implement
human oversight with explicit bias-checking procedures. Document your
bias assessment process. Consider whether AI use should be disclosed to
affected parties. For applications affecting individual rights or
opportunities, bias testing isn't optional --- it's an ethical
requirement.

### Question 5: Am I Maintaining My Professional Judgment, or Am I Delegating It to AI?
This is the ultimate question. AI is a tool to enhance your judgment,
not replace it.

The Rule: ABA Model Rule 1.1 requires lawyers to provide "competent
representation." Model Rule 5.3 requires lawyers to supervise
non-lawyers (which includes AI systems).

You're responsible for the work product. "The AI did it" isn't a
defense.

The Framework:

Appropriate use means AI assists your judgment. AI summarizes a
deposition while you analyze the testimony and determine its impact on
your case. AI drafts a contract while you review every clause for
accuracy and client-specific appropriateness. AI organizes discovery
documents while you review flagged documents and make final relevance
determinations. AI suggests research terms while you evaluate the
results and determine which authorities to cite.

Inappropriate use means AI replaces your judgment. AI generates a brief
and you submit it without careful review. AI recommends a legal strategy
and you advise the client to follow it without independent analysis. AI
assesses litigation risk and you quote the assessment to the client
without evaluating the underlying factors. AI flags privilege issues and
you rely on AI determinations without applying your own professional
judgment.

April Dawson, an attorney and IBM SkillsBuild advocate, frames it
clearly: "AI is not going to replace you. What it's going to do is it's
going to help you do what you do faster. It can help you augment what
you're doing... it's helping you become better as an attorney." The key
word is "augment." AI should make your judgment more efficient, not
eliminate it.

The Action: Before using AI output in any client communication or court
filing, ask: "Have I applied my own professional judgment to this?" If
the answer is no, you're not done.

### Putting It All Together: A Decision Tree
Here's how to apply these five questions to any task:

#### Task: Summarize a 300-page deposition transcript
> Q1: Is this confidential?\
> Yes --- use enterprise AI tool with BAA, not public ChatGPT.

> Q2: Am I asking for legal citations?\
> No --- asking for factual summary.

> Q3: Can I verify the output?\
> Yes --- I can check the summary against the actual transcript.

> Q4: Could bias affect the output?\
> Low risk --- factual summary task.

> Q5: Am I maintaining judgment?\
> Yes --- I'll review the summary and apply my own analysis to determine
> significance.

Decision: Proceed with enterprise AI tool. Verify summary accuracy.
Apply independent judgment to analysis.

#### Task: Find cases supporting summary judgment on employment discrimination claim
> Q1: Is this confidential?\
> Case facts are confidential --- redact specifics or use enterprise
> tool.

> Q2: Am I asking for legal citations?\
> Yes --- this is exactly where Mata v. Avianca went wrong.

> Q3: Can I verify the output?\
> I must verify every citation in Westlaw/Lexis.

> Q4: Could bias affect the output?\
> Employment discrimination is high-risk for bias.

> Q5: Am I maintaining judgment?\
> I must read the cases and determine which support my argument.

Decision: Proceed cautiously. Use AI to suggest research terms and
potential issues. Verify every citation independently. Read all cases in
full. Apply professional judgment to argument construction.

#### Task: Generate engagement letter for new client
> Q1: Is this confidential?\
> Client name and matter description are confidential --- redact or use
> enterprise tool.

> Q2: Am I asking for legal citations?\
> No --- drafting task.

> Q3: Can I verify the output?\
> Yes --- I can review the draft against my standard forms and client
> needs.

> Q4: Could bias affect the output?\
> Low risk for engagement letters.

> Q5: Am I maintaining judgment?\
> Yes --- I'll customize for this client and matter.

Decision: Proceed. Use AI to generate first draft based on my standard
form. Review carefully. Customize for client. Don't send without
thorough review.

#### Task: Assess likelihood of success in proposed litigation
> Q1: Is this confidential?\
> Yes --- client matter. Use enterprise tool or don't use AI.

> Q2: Am I asking for legal citations?\
> Partially --- assessing based on case law.

> Q3: Can I verify the output?\
> Difficult --- requires judgment about how courts would rule.

> Q4: Could bias affect the output?\
> Potentially high --- litigation outcomes may reflect historical
> biases.

> Q5: Am I maintaining judgment?\
> This is pure professional judgment --- AI can't replace it.

Decision: Don't use AI for final assessment. Might use AI to organize
relevant case law or identify factors, but the ultimate assessment must
be my professional judgment based on experience, not AI prediction.

### The Bottom Line
AI can accelerate legal work dramatically --- if used appropriately. The
five questions provide a framework. Consider confidentiality: is the
information protected, and do you have appropriate data protection?
Examine citations: are you asking AI to generate or verify legal
authority? Don't. Assess verification: can you check AI output against
source documents? Evaluate bias: could biased training data affect this
output? Maintain judgment: are you applying your professional judgment
or delegating it?

If you can't answer all five questions confidently, don't proceed --- or
modify your approach until you can.

The lawyers who master this framework will use AI safely and
effectively. The lawyers who skip these questions will eventually face
the consequences Steven Schwartz did: sanctions, embarrassment, and
potential disciplinary action.

Which will you be?
::::Quick Reference Checklist

Before using AI for any legal task, ask:

☐ Confidentiality: Is this confidential information? Do I have
appropriate data protection?

☐ Citations: Am I asking AI to generate or verify legal citations? (If
yes, stop --- verify everything independently in Westlaw/Lexis)

☐ Verification: Can I verify AI output against source documents?

☐ Bias: Could biased training data affect this output? Have I assessed
bias risk?

☐ Judgment: Am I applying my own professional judgment to the output?

If you can answer all five confidently, proceed with appropriate
verification procedures. If not, reconsider your approach.
::::::::::::By [Kyle Jones](https://medium.com/@kyle-t-jones) on
[November 5, 2025](https://medium.com/p/0087da723bb9).

[Canonical
link](https://medium.com/@kyle-t-jones/five-questions-every-lawyer-must-ask-before-using-ai-0087da723bb9)

Exported from [Medium](https://medium.com) on November 10, 2025.
