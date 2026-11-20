# Reflection from Part A: Concept Analysis

## i. What is Agentic Software Engineering?
Agentic Software Engineering is the practice of building software where AI agents do more than answer a single prompt. They plan steps, use tools, write or test code, and work toward a goal with some independence. As I understand it, the engineer's job shifts a little: instead of writing every line, we design the agent, set its limits, and check its work. It still follows the usual software development life cycle (SDLC), meaning requirements, design, testing, and maintenance, plus habits like version control, just applied to something that does not always behave the same way twice.

## ii. How does an AI agent differ from a traditional software application?
A traditional application follows fixed rules written by a programmer. The same input gives the same output, and every path was decided ahead of time. An AI agent is given a goal and decides its own steps. Russell and Norvig describe an agent as something that perceives its environment and acts on it to reach a goal, so it can choose different actions depending on what it sees. That makes an agent more flexible, but also harder to predict and harder to test, because we cannot list every possible behavior beforehand.

## iii. Why are Agile methods appropriate for developing agentic systems?
Agile repeats the SDLC in small cycles instead of one long line, which suits agentic systems because they are hard to fully specify at the start. We usually do not know how an agent will behave until we try it. Scrum's short sprints let a team build a small piece, watch what the agent actually does, and adjust. Sprint reviews and retrospectives give regular chances to catch bad behavior early, and the product backlog can change when new problems show up. Frequent feedback is safer than finishing one big plan and only then finding out the agent misbehaves.

## iv. What risks should developers consider when deploying autonomous AI agents?
First, agents can produce wrong or made-up information and still act on it confidently. Second, there are security risks like prompt injection, leaked credentials, or an agent that has more permissions than it needs. Privacy is another concern when agents handle personal data. There is also bias, which can lead to unfair decisions, and accountability, since it can be unclear who is responsible when an agent makes a mistake. Finally, an agent acting on its own can do damage fast, like deleting files or sending messages, before anyone notices. The NIST AI Risk Management Framework treats these as risks to be identified and managed, not ignored.

## v. Why is human oversight important in AI-enabled applications?
AI does not understand consequences the way people do. A human can review risky actions, correct mistakes, and take responsibility for the outcome. Keeping a person in the loop for important decisions, like approving code merges or anything involving money or personal data, adds a safety net. It also builds trust, since users feel better knowing someone is accountable. The Govern function in the NIST framework talks about clear roles and accountability, and I think that is the main point: AI can assist, but people stay in charge.

