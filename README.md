# SD5913 Assignment

Formal repository for the SD 5913 assignment upload.

# Draft Outline of the Essay

## Central Thesis

AI may make manual code production cheaper and faster, but that does not make programming irrelevant to design. For an interaction designer, learning programming is a way to turn ambiguous intentions into explicit behaviours, to test and judge what a machine produces, and to understand how computational systems shape what can be imagined. The syntax may change or become automated; the judgement needed to specify, evaluate, and revise interactive systems is more likely to survive.

## Argument Map

1. Programming exposes the gap between describing an experience and specifying how it should behave.
2. In an AI-assisted workflow, reading, testing, and judging code can matter more than writing every line by hand.
3. Understanding computation changes the designer’s imagination because the medium itself introduces states, conditions, parameters, feedback, and constraints.
4. Even if many current programming techniques become obsolete, specification, evaluation, iteration, and authorship remain meaningful design questions.

## Detailed Paragraph Plan

### 1. Introduction — From “Good Interaction” to Executable Behaviour

- Target length: 80–100 words
- Purpose: Open with one of the two portfolio product-design projects. Explain that what first attracted me to interaction design was not only how a product looked, but how it responded to a person over time.
- Personal evidence: Refer briefly to a moment in the project where the product had to react to user input, movement, choice, timing, or another changing condition. The exact project name and interaction should be used in the final essay.
- Key move: Shift from the visible experience to the invisible logic behind it: an interaction that feels “natural” to a user still has to be translated into precise rules.
- End of paragraph: State the thesis: I do not need to learn programming in order to beat AI at code generation; I need it to understand and direct the behaviour of the systems I design.

### 2. Portfolio Project 1 — The Gap Between Describing and Specifying

- Target length: 170–200 words
- Main claim: Design language is often intentionally loose: “smooth,” “responsive,” “intuitive,” or “playful.” A computer cannot act on those words until they are converted into conditions, states, thresholds, timing, and exceptions.
- Personal evidence: Use the first portfolio project to show how one seemingly simple interaction had to be broken down into rules. For example, explain what had to be decided about when an interaction starts, what changes, how long the change lasts, and what happens if the user behaves differently from the expected path.
- Analysis: The value of programming here is not memorising syntax. It is the discipline of making an intention precise enough to be executed, tested, and revised.
- Source integration: Use Ada Lovelace’s Note G as a historical frame. Her point that the Analytical Engine performs what humans know how to order it to perform is useful because it highlights the difference between an intention and an executable instruction (Lovelace, 1843).
- Link back to thesis: Programming therefore becomes part of design thinking: it forces me to make decisions that a visual mock-up can leave unresolved.

### 3. Portfolio Project 2 — Working Code Is Not the Same as Good Design

- Target length: 150–180 words
- Main claim: AI can make the first technical implementation easier, but a functioning prototype can still be a poor interaction.
- Personal evidence: Use the second portfolio project to describe a real moment when testing or iteration revealed that the first implementation needed revision. The issue could involve feedback, timing, state changes, hardware response, user confusion, or another problem actually encountered in the project.
- Analysis: This is where code literacy matters even if the code itself is partly machine-generated. I need enough understanding to inspect behaviour, ask why it happened, distinguish a technical bug from a design problem, and decide what to change.
- Source integration: Connect this to the Agile principles: working software is treated as a meaningful measure of progress, but the same principles also emphasise responding to change, technical excellence, good design, and regular reflection and adjustment (Beck et al., 2001).
- Link back to thesis: The designer’s role moves from merely requesting output to evaluating and directing an iterative system.

### 4. Programming as a Design Material

- Target length: 140–170 words
- Main claim: Learning a medium changes what I notice and what I can imagine. Programming introduces concepts such as state, condition, parameter, randomness, sensor input, latency, and real-time feedback.
- Personal reflection: Before learning programming, I could think mainly in terms of form, layout, sequence, and visible interface. With computational thinking, I can also design relationships and behaviours that unfold over time.
- Source integration 1: Dylan Beattie’s The Art of Code is useful because it treats code as an expressive medium, including generative art and live coding, rather than only as an engineering utility (Beattie, 2019).
- Source integration 2: Don Ihde’s postphenomenological approach, as summarized by Introna, argues that technologies mediate human–world relations rather than acting as neutral channels. This supports the idea that not understanding the medium can limit what a designer perceives as possible (Introna, 2024).
- Link back to thesis: Programming is therefore not just a production skill delegated to engineers or AI; it is part of the conceptual vocabulary of interactive design.

### 5. The Uncomfortable Case — What If Today’s Coding Skills Become Obsolete?

- Target length: 120–150 words
- Counterargument: Take the strongest objection seriously: perhaps many languages, frameworks, and debugging routines taught now will be automated or outdated during my career.
- Response: If that is true, syntax is the weakest reason to learn programming. The stronger reasons are specification, reading, testing, judgement, iteration, and the ability to form a mental model of how an interactive system behaves.
- Historical comparison: Use the 1965 computer-art history only as a limited analogy, not as proof that AI will be harmless. Georg Nees and Frieder Nake were among the early pioneers of publicly exhibited algorithmic art; the arrival of computers changed artistic practice and authorship rather than simply ending art (Digital Art Museum, 2022).
- Qualification: This time may still be different because generative AI operates at a much broader scale. That uncertainty is precisely why understanding the medium matters: it gives me a basis for judgement rather than dependence on opaque output.

### 6. Conclusion — I do not need to beat the machine

Target length: 80–100 words

Return to the question: Answer “Why are we here?” directly and personally.

Final position: I am not learning programming because I expect to write code faster than AI. I am learning it so that I can define what an interactive system should do, recognise when the result is wrong or inadequate, and use computation deliberately as part of design.

Closing idea: If AI changes programming beyond recognition, the course is still valuable to me insofar as it develops the judgement required to work with — and not merely underneath — increasingly automated systems.


### Why Are We Here?

When I first learned to design, I mostly thought about form, layout, visual hierarchy, and user experience. However, while developing interactive products, I began to realise that an experience is not defined only by what a product looks like. It is also defined by how the product responds to a person over time. A simple interaction may depend on a sequence of conditions, states, timing, and feedback that are invisible to the user. This makes me question why I should still learn programming when, in 2026, AI can already generate working code from a sentence. My answer is not that I need to write code faster than AI. I need to learn programming so that I can specify, evaluate, and shape the behaviours of the systems I design.

My experience with MindSprout, a mobile application designed to support retirees through horticultural activities, showed me the gap between describing an experience and specifying one. As a designer, I could say that I wanted the interface to feel simple, intuitive, and supportive. But these words are not instructions that a computer can execute. A system needs to know what happens when a user taps a button, what state changes afterward, what information appears next, and what should happen when the user does something unexpected. Ada Lovelace made a related observation in her Note G on the Analytical Engine: the machine could do what humans “know how to order it to perform” (Lovelace, 1843). For me, this is the important part of programming. It forces a design intention to become precise enough to be executed, tested, and changed. A visual prototype can make an interaction look resolved while leaving its behavioural logic undefined. Programming exposes those unresolved decisions.

My second project, PureProbe, made me think about another problem: working code is not necessarily good design. PureProbe is an educational food-sorting toy using an Arduino scanner, colour sensing, lights, vibration, and voice feedback. A child scans a food card, and the system responds according to the classification. On paper, this sounds straightforward: input, recognition, and feedback. In practice, however, the timing and clarity of that feedback affect whether the interaction feels understandable to a child. A system may function technically while still producing confusing or ineffective behaviour. This is why I find the Agile principles relevant. They treat working software as an important measure of progress, but they also emphasise responding to change, technical excellence, good design, and regular reflection and adjustment (Beck et al., 2001). In an AI-assisted workflow, I may not write every line myself, but I still need enough programming knowledge to read what has been produced, understand why it behaves in a certain way, distinguish a technical error from a design problem, and decide what should change next. The designer therefore becomes not only a requester of code, but an evaluator of behaviour.

Learning programming also changes what I consider to be a design material. Turing’s On Computable Numbers approached computing from a fundamental question: what can be calculated by a machine? His description of a computing machine makes computation understandable as a process of states, configurations, symbols, and rules (Turing, 1936). This way of thinking introduces a vocabulary that is different from traditional visual design. Instead of thinking only about form or sequence, I can begin to think about conditions, parameters, randomness, sensor input, feedback, and state changes. Dylan Beattie’s The Art of Code similarly presents programming as a medium for creative expression rather than merely a technical utility (Beattie, 2019). For a designer, understanding this medium matters because the material itself influences what can be imagined.

This connects to Don Ihde’s idea of mediated perception. Technologies are not simply neutral tools placed between humans and the world; they shape how relationships with the world are experienced and what becomes visible or possible (Introna, 2017). If I do not understand programming, I may not simply be missing a technical skill. I may also be missing a range of possible interactions that I do not yet know how to imagine. Before learning computational thinking, I might mainly ask what an interface should look like. With programming, I can also ask how a system could respond, adapt, remember, transform, or generate in real time. In this sense, learning the medium expands the design space itself.

Still, the uncomfortable possibility remains: perhaps much of what I learn in this course will become obsolete during my career. Programming languages, frameworks, and even debugging techniques may increasingly be automated. I do not think this possibility should be dismissed. In fact, it makes me less interested in treating syntax as the main reason to learn programming. The history of computer art offers a useful comparison. In 1965, Georg Nees and Frieder Nake were already creating artworks through computer programs, transferring part of the making process to machines. Their experiments did not simply eliminate artistic practice; they introduced a different relationship between human decisions, algorithms, and machine production (Digital Art Museum, 2022). AI may be a much larger transformation, so history cannot prove that the future will be the same. But it suggests that when production becomes automated, questions of intention, judgement, and authorship do not disappear.

So why are we here? I am not learning programming because I expect to compete with AI at writing code. I am here to learn how computational systems behave, how to describe what I actually want them to do, and how to recognise when their output is wrong, inadequate, or unexpectedly valuable. If AI eventually writes most of the code, that may make programming as a manual craft less important. But it makes specification, evaluation, iteration, and judgement more important to me as a designer. I do not need to beat the machine at writing code. I need to understand enough about the medium to decide what the machine should make possible.
