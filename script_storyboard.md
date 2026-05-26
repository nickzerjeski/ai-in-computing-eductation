# AI in Computing Education — 12-Minute Video Script and Storyboard

**Central message:**  
AI should not be treated as either a shortcut to ban or a magic tutor to trust. In computing education, the real question is how to design learning environments where AI supports understanding, critical thinking, and responsible use.

**Approximate narration speed:** 125–135 words/minute  
**Target audience:** Non-specialist audience  
**Style:** Modern, visually engaging animation

---

## 12-Minute Storyboard and Script

| Time | Scene / visual storyboard | Narration script |
|---:|---|---|
| **0:00–0:45** | **Cold open.** Fast modern animation: a student sits in front of a laptop. Three AI bubbles pop up: “Generate code”, “Explain this error”, “Grade this diagram”. The screen fills with green checkmarks, then glitches into warning icons: “Wrong?”, “Biased?”, “Too easy?” | Imagine a student learning programming. They get stuck. Instead of asking a teacher, searching Stack Overflow, or debugging for half an hour, they ask an AI assistant: “Fix my code.” In seconds, the AI gives an answer. That feels powerful. But now we have a problem: did the student learn anything? Is the answer correct? Can they explain it? And should we even allow this in education? This video is about AI in computing education — not as hype, and not as panic, but as a design challenge. The question is no longer simply: “Can students use AI?” They already can. The harder question is: “How do we teach computing when AI is part of the environment?” |
| **0:45–1:30** | **Title scene.** Text appears: “AI in Computing Education: Tool, Tutor, or Trap?” Background: animated classroom transforming into IDE, chatbot, diagram tool, image generator. | Generative AI is changing computing education because computing is one of the fields where AI can directly act on the learning material. It can write code, explain code, debug code, generate tests, assess software artifacts, and even create learning material. Recent research argues that banning these tools is neither practical nor educationally sufficient; instead, the focus should shift toward understanding, adopting, and adapting AI tools so that they serve educational goals. So the core idea of this video is: AI in computing education is not one thing. It is sometimes a tutor, sometimes a collaborator, sometimes an assessment assistant, and sometimes a shortcut that bypasses learning. |
| **1:30–2:30** | **Map scene.** Animated “AI learning ecosystem”: Student ↔ AI ↔ Teacher ↔ Team ↔ Assessment. Icons for code generation, explanation, feedback, grading, bias reflection. | To understand the field, we can divide AI in computing education into five roles. First, AI as a **code generator**, helping students produce programs. Second, AI as a **code explainer**, helping students understand existing or generated code. Third, AI as a **tutor or lab assistant**, giving hints and feedback. Fourth, AI as a **team member**, helping with brainstorming, review, and project work. Fifth, AI as an **assessment assistant**, helping evaluate diagrams, code, or explanations. Each role has benefits, but each also creates risks. A code generator can help students get started, but it can also replace their thinking. A code explainer can reduce confusion, but it can hallucinate. A grading assistant can save teacher time, but it may misunderstand the criteria. |
| **2:30–3:35** | **Non-expert programmer ladder.** Visual: “Code Runner → Code Adaptor → Code Writer → AI-supported Code Builder.” Show a restaurant manager, scientist, consultant using AI to code. | One promise of AI is that it could make programming more accessible. Feldman and Anderson study non-expert programmers — people who do not have deep formal CS training but still need to perform programming tasks at work. They describe a spectrum: some people are “code runners” who can run existing code, others are “code adaptors” who can modify code, and experts are “code writers.” Code LLMs could flatten this hierarchy by allowing more people to express intent in natural language and generate working programs. But this promise depends on a hidden assumption: that non-experts can communicate effectively with the AI and evaluate what it produces. Without those skills, AI may not reduce the gap between experts and novices. It may widen it. |
| **3:35–4:35** | **Prompting breakdown animation.** A natural language prompt enters AI. Output code appears. Then four checkpoints animate: “intent”, “prompt”, “output”, “revision”. Some fail in red. | Working with an AI coding assistant is not just “ask and receive.” It is a loop. First, the learner must form an intent. Then they must describe that intent precisely. Then they must inspect the generated code. Then they must revise either the code or the prompt. Feldman and Anderson found that non-programmers struggle with this loop, especially with technical communication. Many participants had trouble describing what they wanted, using the “right” technical language, and understanding why the model interpreted their prompt differently. This matters because programming language is precise. In everyday speech, “group,” “list,” and “set” may feel similar. In computing, they can mean very different things. So AI does not remove the need for computing knowledge. It shifts the need from writing everything yourself to specifying, checking, and revising. |
| **4:35–5:35** | **Code comprehension scene.** Student watches AI generate code. The camera zooms from “writing code” to “understanding code”. Text: “From coding to comprehending.” | This leads to one of the most important shifts: AI changes programming education from mainly writing code to also understanding AI-generated code. Qiao and colleagues describe code comprehension as the process of building a mental model of what code does. Their systematic review argues that as programmers rely more on AI-generated solutions, it becomes increasingly important to understand, verify, and integrate those solutions. This is not a minor skill. In real software development, code comprehension already takes a large part of maintenance and evolution work. AI makes this skill even more central. The student of the future may spend less time typing every line from scratch, but more time asking: “What does this code do? Is it correct? Does it fit the problem? Can I trust this explanation?” |
| **5:35–6:45** | **Two chatbot comparison.** Split screen: left “Unrestricted chatbot” gives full answer; student copies. Right “Assistant chatbot” gives hints, asks questions, points to concepts. Learning meter rises more on right. | The design of the AI assistant matters. Noraset and colleagues compared different chatbot conditions in a short Python programming course: no chatbot, an unrestricted chatbot, and a constrained assistant chatbot. The assistant chatbot was designed to guide students without directly giving full solutions. Students using this assistant showed greater improvement from pre-test to post-test than those using the unrestricted chatbot. This supports a key educational principle: AI should scaffold learning, not simply solve the task. But the study also found a practical problem. Students preferred free-text prompts, and some tried to exploit the chatbot to get complete solutions. The constrained assistant reduced misuse compared with the unrestricted chatbot, but it remained vulnerable to prompt injection and jailbreaking attempts. The lesson is not “restricted AI solves everything.” The lesson is that interaction design, guardrails, and classroom norms all matter. |
| **6:45–7:55** | **Team project animation.** Five students around a project board. AI appears as three avatars: “assistant”, “peer”, “educator”. Then warning icons: “unchecked code”, “hidden skill gaps”, “accountability”. | AI also changes teamwork. Kharrufa and colleagues studied students using generative AI in a semester-long software engineering team project. They found that AI played several roles: as an educator, giving explanations and examples; as a peer, reviewing code or documents and helping brainstorm; and as an assistant, writing boilerplate, tests, or helping fix bugs. Students reported that AI could bridge skill gaps inside teams and increase confidence, because weaker team members could contribute more effectively with AI support. But the same mechanism creates a risk: if students contribute AI-generated code they do not understand, teams may receive buggy or subpar work, and it becomes harder to know each member’s real ability. So in team projects, AI is not just an individual tool. It affects accountability, trust, workload distribution, and peer learning. |
| **7:55–8:55** | **Assessment scene.** Teacher grading many UML diagrams. AI assistant highlights elements. Some scores match; others diverge. Overlay: “Useful assistant ≠ replacement.” | AI can also support assessment. Wang and colleagues investigated whether GPT can assess UML use case diagrams, class diagrams, and sequence diagrams in software engineering education. Their study used 40 student reports and compared GPT grading with human expert grading. The result is nuanced: GPT could perform the assessment task with detailed criteria, but it generally gave lower scores than human experts and could not fully replace them. The researchers identified discrepancy types such as misunderstanding, overstrictness, wrong identification, reasonable identification, and perfect match. This is a useful model for educational AI: AI can reduce workload, generate draft feedback, and highlight issues, but high-stakes assessment still needs human oversight. A good use case is not “AI grades everything.” A better use case is “AI assists the teacher, and the teacher remains responsible.” |
| **8:55–9:55** | **Bias reflection scene.** Text-to-image generator receives prompts: “nurse”, “professor”, “engineer”, “criminal”. Generated silhouettes become stereotyped, then students add sticky notes: “gender?”, “age?”, “ethnicity?”, “harm?” | Computing education is not only about programming skills. It is also about understanding how AI systems behave in society. Apiola, Vartiainen, and Tedre studied first-year CS students who used text-to-image generators and reflected on bias, harms, and possible fixes. Their data included 163 student reports. Students observed biases related to gender, ethnicity, age, and other categories, and they attributed bias both to society and to data or algorithms. A concrete example: all students who generated images for “nurse” reported gender bias, because the images were mostly or entirely female. Many also observed ethnicity and age biases. This is important because computing students should not only ask, “Can I build this system?” They must also ask, “What assumptions does it reproduce? Who might be harmed? In what context would this output matter?” |
| **9:55–10:55** | **Design principles scene.** Three large animated levers: “Role”, “Scaffolding”, “Transparency”. A user adjusts sliders to move AI from “answer machine” to “learning partner”. | Across the papers, a pattern emerges: the educational value of AI depends less on the raw model and more on the surrounding design. Kharrufa and colleagues propose thinking about AI tools through roles, scaffolding, and transparency. Is the AI acting as an educator, a peer, or an assistant? How much support does it give, and when does that support fade? Who can see how AI was used — the learner, the team, or the teacher? Qiao and colleagues make a similar point for code comprehension: students need to verify AI explanations, instructors should design assessments that avoid learning circumvention, and tool builders should include validation mechanisms such as human-in-the-loop checks or confidence estimates. In simple terms: good AI learning tools should not just provide answers. They should keep students cognitively active. |
| **10:55–11:40** | **New curriculum scene.** Four modules appear as cards: “Fundamentals”, “Prompting”, “Verification”, “Ethics”. Students move through them like a learning path. | So what should computing education teach now? First, fundamentals still matter. Students need enough programming knowledge to reason about AI-generated code. Second, technical communication matters: students must learn how to express computational intent precisely. Third, verification matters: students must test, debug, and critique AI outputs instead of treating them as truth. Fourth, ethics and social impact matter: students must understand bias, misuse, privacy, and fairness. Finally, assessments should shift from only asking students to produce final artifacts toward asking them to explain, critique, revise, and document their process. Qiao and colleagues explicitly recommend moving from product-only tasks toward process-based assignments, such as critiquing AI-generated code or using AI to explain code and find bugs. |
| **11:40–12:00** | **Closing scene.** Return to first student. This time, the AI answer appears, but the student checks tests, annotates code, discusses with team, and writes reflection. Final text: “AI should not replace learning. It should be designed into learning.” | The future of AI in computing education is not a simple yes-or-no question. AI can help students access programming, understand code, receive feedback, and work in teams. But it can also hide misunderstanding, enable shortcuts, reproduce bias, and weaken assessment. The central challenge is design. When AI is an answer machine, it can bypass learning. When AI is a scaffolded, transparent, critically used tool, it can support learning. So the goal is not to teach students without AI, and not to let AI do the learning for them. The goal is to teach students how to think with AI — and how to know when not to trust it. |

---

## Recommended Visual Style

Use a **modern flat-motion / kinetic typography style**:

- Dark background
- Neon accent colors
- Clean icons
- Smooth transitions
- Code snippets animating like data streams
- Simple, non-distracting human characters

The most important recurring visual metaphor should be the **AI dial**: depending on design, the same AI moves between:

- **Shortcut**
- **Assistant**
- **Peer**
- **Scaffold**

For engagement, repeat one visual question throughout the video:

> **Who is doing the thinking?**

That question connects all sections: code generation, comprehension, chatbot design, teamwork, assessment, and ethics.

---

## Source Mapping

Use the following papers to support the claims in the video:

| Topic in video | Main supporting paper |
|---|---|
| Bias and social justice in generative AI | Apiola, Vartiainen, and Tedre (2024), *First Year CS Students Exploring And Identifying Biases and Social Injustices in Text-to-Image Generative AI* |
| Non-expert programmers and Code LLMs | Feldman and Anderson (2024), *Non-Expert Programmers in the Generative AI Future* |
| AI in software engineering team projects | Kharrufa et al. (2026), *LLMs Integration in Software Engineering Team Projects* |
| Chatbot design in programming education | Noraset et al. (2026), *Evaluating lab assistant chatbot on student learning and behaviors in a programming short course* |
| GenAI for code comprehension | Qiao, Shihab, and Hundhausen (2026), *A Systematic Literature Review of the Use of GenAI Assistants for Code Comprehension* |
| GPT for UML assessment | Wang et al. (2026), *Assessing UML diagrams by GPT: Implications for education* |

---

## Production Notes

### Suggested pacing

The script is designed for a 12-minute video at a moderate narration speed. During production, leave short pauses after key statements such as:

- “Who is doing the thinking?”
- “AI does not remove the need for computing knowledge. It shifts it.”
- “Useful assistant does not mean replacement.”
- “AI should not replace learning. It should be designed into learning.”

### Suggested recurring transitions

Use the same transition pattern between major sections:

1. A question appears.
2. The AI interface animates.
3. The scene zooms out to show the educational context.

Example:

> “But what happens when the learner cannot judge the answer?”

This can transition from code generation into code comprehension.

### Suggested ending frame

Final text on screen:

> **AI should not replace learning.  
> It should be designed into learning.**

