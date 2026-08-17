<h1 align="center">Halyna Lavrik</h1>

<p align="center">
  <b>AI systems engineer · Chicoutimi, Québec</b><br>
  I build AI administrators for small and mid-sized businesses,<br>
  and I write down the setup that makes them reliable.
</p>

<p align="center">
  <a href="https://lavrikgeo.com">lavrikgeo.com</a> ·
  <a href="mailto:nova@lavrikgeo.com">nova@lavrikgeo.com</a> ·
  <a href="https://github.com/Lavrik-nova?tab=repositories">Repositories</a>
</p>

---

### What I do

An **AI administrator** is not a chat bot with scripted replies. It is a
reasoning system that reads what a customer actually asked — often two questions
in one sentence, in a language they switch mid-message, about a product they are
describing wrong — and either answers correctly from facts the business holds, or
says it cannot and hands over.

Getting the second half right is most of the work.

I build these for manufacturers and service businesses, and I document the
engineering rather than the outcome, because the engineering is the part that
transfers.

---

### Repositories

| | |
|---|---|
| **[claude-code-and-agent-architecture](https://github.com/Lavrik-nova/claude-code-and-agent-architecture)** | How I configure Claude Code before building anything — code graph, adversarial critics, harness, three memory layers — and the reasoning stack of the AI administrator it produced. Decision log included: every choice with the options that lost. |
| **[architecture-agent-et-claude-code](https://github.com/Lavrik-nova/architecture-agent-et-claude-code)** | La même chose, en français. |

---

### How I work

<details>
<summary><b>Three rules that shape everything I build</b> — click to expand</summary>

<br>

**A control must be code, a flag or a test.**
Telling a model not to do something is a request, not a control. On a production
system, three separate attempts to fix behaviour by adding a sentence to a prompt
were rolled back. The constraint now lives where the model cannot decline it —
for example, the review filter on the knowledge base sits inside the SQL query,
so no caller can bypass it, including one written next year by someone who never
read the rule.

**Rejecting is the main work.**
A knowledge base that accepts everything is a landfill, and a landfill is worse
than an empty folder because it looks like an asset. Roughly two-thirds of what I
read gets refused in writing, with a named reason. What survives carries its
source, its date, and whether it is primary or secondary — because secondary
material never settles a decision on its own.

**A decision without its rejected options is an announcement.**
Every architectural choice I make is recorded with what else was considered, what
it costs, and the condition under which it gets reopened. Without that last
field, a decision becomes folklore: everyone follows it, nobody remembers why,
and it outlives the situation that justified it.

</details>

<details>
<summary><b>What I am currently missing</b> — click to expand</summary>

<br>

No controlled comparison of my setup against no setup. I have a decision log,
production behaviour, and criteria fixed in advance — not an experiment. Building
that experiment is the next piece of work, and until it exists I am not going to
quote a percentage at anyone.

A deny-list for credential paths in my own permission configuration. The
allow-list grew by accretion, which is exactly the accumulation pattern I warn
about elsewhere. It is next, not done.

</details>

---

<p align="center">
  <sub>Français, English, Українська · Available for consulting work</sub>
</p>
