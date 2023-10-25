# Audiense Product Engineering Principles
Guiding principles that serve as a blueprint for decision-making when developing and designing products at Audiense.

# How do we utilize these principles?
To effectively implement these principles, **it is essential to embrace and apply them collectively**. Concentrating on each principle in isolation could lead us towards overly extreme or unbalanced applications.

Here’s a breakdown of how we incorporate these principles into our operations:

- **Evaluate designs**: Principles can help identify any crucial aspects that might be missing when creating something new, such as a process or a software product.
- **Onboarding**: Principles can be used to instruct new team members about our work methodologies, helping them get up to speed more quickly.
- **Hiring**: Principles ensure that we onboard individuals who align with our principles. The principles act as a filter, attracting candidates who align with the company's values and deterring those who might not be a good fit.
- **Post-mortems**: By comparing failures against principles, we can identify what went wrong and potentially adjust the principles themselves to improve in the future.
- **Reviews**: Since principles guide behaviour, they can also be used to review and assess performance. Principles serve as useful lenses for conducting reviews, as they go beyond pure performance metrics.

For each principle definition, we have the following sections:

- **A catchy name**: This helps create a shared language for daily work that is easy to remember.
- **Practices and Techniques**: These are suggested practices and techniques that can assist in adhering to the principles. Their adoption is not mandatory, nor are they intended as strict rules to measure compliance with the principles.
- **Audiense Values**: These are the Audiense values that are related to each principle.
- **How do we know if we are not following it?**: These are examples of situations where the principles may not be adhered to. This list is not exhaustive, so it should not be used as a checklist.



## **[Ask Why](#ask-why)**

- Connect work to business outcomes.
- Understand the real problem being solved.
- Asking "why" is part of the team culture.

### **Key Signs of Not Following:**

- Unsure of stakeholders' needs or the problem being solved.

## **[Take Risks](#take-risks)**

- Encourage experimentation and learning from failure.
- Ensure risks are taken with the proper safety net.
- Understand and anticipate the impact of changes in production.

### **Key Signs of Not Following:**

- Reluctance to try new things, extended validation times, missing learning opportunities from failures, and affecting other teams without coordination.

## **[WIP=1](#wip1-work-in-progress--1)**

- Focus on delivering the highest value first.
- Challenge starting multiple features at once.
- Avoid knowledge silos and focus on team collaboration.

### **Key Signs of Not Following:**

- Multiple initiatives are being tackled simultaneously, large commits with unrelated changes, working in isolation, and frequent multitasking.

## **[Always Ready to Ship](#always-ready-to-ship)**

- Be prepared to deploy at any time.
- Aim for early feedback and outcome measurement.
- Reduce the accumulation of uncommitted or undeployed code.

### **Key Signs of Not Following:**

- Starting new services without integration, waterfall-like technical tasks, and long periods without real user feedback.

## **[Stay Sharp](#stay-sharp)**

- Reduce cognitive load through various means.
- Invest in technical skills and understand the business domain.
- Don't feel unproductive while investing time in improving your skills and tools.

### **Key Signs of Not Following:**

- Repeatedly retrying tests, spending excessive time on manual tasks, and recurring unresolved challenges.

## **[Software is a Means to Achieve an Outcome](#software-is-a-means-to-achieve-an-outcome)**

- Recognize software as both an asset and a liability.
- Defer commitments and make cost-effective decisions.
- Aim to reduce complexity and unnecessary code.

### **Key Signs of Not Following:**

- Writing complex unvalidated code, not cleaning obsolete code, and introducing irrelevant technologies.

## **[Courage and Respect](#courage-and-respect)**

- Prioritize the values of courage and respect in decision-making.
- Courage is about upholding principles, even against popular opinions.
- Create an environment of psychological safety and open communication.

### **Key Signs of Not Following:**

- Avoiding necessary refactorings, criticizing without understanding, being defensive against feedback, and team members feeling unable to express themselves.


# The principles explained

## Ask Why

No matter how far your team is from your end-users, there is always a way to connect your work to product and business outcomes. Challenge solutions if you don’t know why you are doing it. We are here to solve problems not to implement solutions.

Asking “Why?” should be part of our culture, so anyone in the company should be able to ask you why you are working on your current task. Ensure you understand why before starting it. Ensure you understand the real problem you are solving.

### **Practices and Techniques**

- Non-violent communication
- Continuous Discovery

### **Audiense Values**

- 🏋️‍♀️ Strive for awesomeness
- ✋ Take ownership
- 🪟 Strive for a culture of transparency

### **How am I able to tell if we are not following it?**

- Do I know why my stakeholders need what I am working on? What is the expected business outcome?
- Do I know what problem I’m solving?

## Take Risks

> “The Third Way of DevOps is about creating a culture that fosters two things: continual experimentation, taking risks and learning from failure, and understanding that repetition and practice is the prerequisite to mastery.”
>— Gene Kim

We want you to experiment, to try things in production. To learn from your mistakes and come back with better solutions.

Let's not confuse this with the courage principle. Taking risks without a safety net is not courage, but rather recklessness.

To take risks, you need the right testing coverage, to know how to roll back your changes under stressful situations. You, as a team, are responsible for your changes. Invest time in having the right tools to go to production safely and understand the impact of your artifacts' work in production.

### **Practices and Techniques**

- Blameless postmortems
- Retrospectives
- Deliberate practice
- Disaster recovery simulations
- Continuous learning
- Non-violent communication
- CI/CD
- Observability
- TDD
- DevOps mindset

### **Audiense Values**

- 🏋️‍♀️ Strive for awesomeness
- ✋ Take ownership

### **How am I able to tell if we are not following it?**

- Did it take days to validate my changes in production?
- Did something not work as expected? Did I miss the opportunity to learn from it and share it with the team?
- When I take risks, do I affect other teams without coordinating with them?
- We avoid unfamiliar technologies or strategies because they're out of our comfort zone.
- Our feedback loops for risk-related projects are too long, showing a reluctance to expose mistakes.
- I don't always prioritize adding testing coverage before making code changes.

## WIP=1 (Work in progress = 1)

> “Best value comes from small, value-focused features, delivered frequently.” 
>— Ron Jeffries

Product development is a team activity. As a team, you should produce the most valuable features first. Challenge the need to start more than one feature at a time. Are you sure there is no more room for other team members to help with the most valuable feature? Challenge the need to go on your own with one task. Aren’t you creating a knowledge silo? How do you expect to avoid that silo? Isn’t this a false sense of parallelism?

This principle can be applied at all levels. Work on atomic commits. Focus on the main goal of that increment. If you notice something to improve, write it down and continue.

### **Practices and Techniques**

- TDD
- Pair or ensemble programming
- Asynchronous code review
- Concerns review
- Continuous discovery
- Boy scout rule

### **Audiense Values**

- 🤜 🤛 Best as a team
- ✅ Do what I say I will do in the right way
- 🤩 Pursuit of happiness

### **How am I able to tell if we are not following it?**

- Is my team working on more than one initiative or feature at a time? Why?
- Am I writing commits that include several unrelated changes?
- Am I working on my own most of the time?
- Are you overwhelmed and multitasking frequently?

## Always Ready to Ship

> “Because we have the best possible product at every moment, we have the best possible product at the moment we decide to ship it. In fact, because we’re always ready, we can ship early if there is any reason to do so—and there often is!”
>— Ron Jeffries 

Our ultimate goal is to produce an outcome, which is different than producing a feature. We should know how to measure the outcome before writing the first line of code. We should be able to ship that line of code as soon as possible so that we can get early feedback, from our tests, our integrations, our production complexities, our users, and finally, measure the outcome.

To accomplish this, we should minimize the accumulation of bits in various stages: unstaged, non-committed, not pushed to the main branch, not deployed to production, and not made available to users.

### **Practices and Techniques**

- Walking skeleton
- Parallel changes
- Trunk-based development
- TDD
- Minimum marketable feature
- Deferred commitment
- Continuous discovery
- Vertical slicing

### **Audiense Values**

- 🏋️‍♀️ Strive for awesomeness
- ✋ Take ownership

### **How am I able to tell if we are not following it?**

- Did we create a new service and start adding functionality to it without a walking skeleton that integrates it through a parallel change strategy?
- Did we split the technical tasks in a way that implies a waterfall of technical layers instead of minimum marketable features?
- We have extended periods without any releases or feedback from real users.

## Stay Sharp

> A woodsman was once asked, “What would you do if you had just five minutes to chop down a tree?” He answered, “I would spend the first two and a half minutes sharpening my axe.”

Cognitive load is one of the main impediments to achieving a sustainable workflow. We must have the courage not to succumb to self-imposed pressure to deliver and invest time in reducing different types of cognitive load:

- Intrinsic: improve our technical skills and knowledge of software design
- Extraneous: enhance our development experience, deliberately practicing procedures and techniques.
- Germane: better understanding of the business domain

We should be able to apply our domain knowledge to solve problems of the right size, minimizing the amount of plumbing and non-business-related effort.

Do not correlate your productivity with the number of hours you spend trying to solve a problem. The less effort you need to achieve your goals, the less stressful your day will be, and the more time and motivation you will have to invest in further reducing cognitive load.

### **Practices and Techniques**

- Deliberate practice
- Domain-driven design
- Ubiquitous language
- Continuous discovery
- Continuous learning
- Pair or ensemble programming
- Architectural decision records
- Concerns review
- Development Experience
- Pomodoro Technique
- Eliminate Toil

### **Audiense Values**

- 🏋️‍♀️  Strive for awesomeness
- 🤜 🤛 Best as a team

### **How am I able to tell if we are not following it?**

- Do I spend time retrying the same tests again and again due to flakiness?
- Does your code use terminology and naming that's different from how the commercial team's customers name things?
- Am I spending too much time on manual, repetitive tasks?
- Do I refrain from deliberate practice or attending training courses because I have too much work?
- Do the same errors or challenges reappear without resolution?

## Software is a Means to Achieve an Outcome

> “Software development is more valuable when it earns money sooner and spends money later. Incremental design explicitly defers design investment until the last responsible moment in an effort to spend money later”
>— Kent Beck 

When designing solutions, it is important to consider that software incurs a fundamental cost and can be seen as a liability. Therefore, it is essential to make cost-effective decisions. Deferring commitment is crucial. By maintaining flexibility and making reversible decisions, we can navigate the uncertain terrain of software development more efficiently.

Often, we try to improve our software by adding more code. However, removing unnecessary or redundant code can be even more beneficial. Eliminating unnecessary code can enhance the efficiency, understandability, and maintainability of our software. Use each refactoring opportunity to reduce unnecessary complexity.

### Practices and Techniques

- Defer commitment
- Refactoring
- Simply design
- Via negativa
- SOLID
- DDD
- Systems Thinking

### Audiense Values

- 🏋️‍♀️ Strive for awesomeness
- ✅ Do what I say I will do in the right way

### How am I able to tell if we are not following it?

- Do you write complex code before validating that your hypotheses are correct?
- Have you removed the source code of discarded iterations?
- Have you introduced new technologies or practices that do not solve real problems?
- Stakeholder communication revolves around deliverables instead of business goals.
- Did you start implementing a solution without understanding its level of availability needs and cost impact?

## Courage and Respect

> “If courage alone is dangerous, in concert with the other values it is powerful. The courage to speak truths, pleasant or unpleasant, fosters communication and trust. The courage to discard failing solutions and seek new ones encourages simplicity. The courage to seek real, concrete answers creates feedback.”
> — Kent Beck

Courage is the effort to achieve or persevere in applying the rest of the principles, even when it means contradicting the opinions of others. It means investing time in something that may not have an immediate outcome, but aligns with our principles.

Courage is not just about heroic acts in epic situations. The other principles should help us minimize the number of dramatic situations.

However, courage without respect can be dangerous. We need to make an effort to understand the needs of everyone.

To act with courage and respect, we must create an environment of psychological safety. This involves fostering open and confident communication, where all voices are heard and taken into account. It also means encouraging asking questions and discussing mistakes.

### Practices and Techniques

- Non-violent communication
- Retrospectives
- Blameless postmortems

### Audiense Values

- 👂 Everyone's voice is valued
- ✋ Take ownership
- ✅  Do what I say I will do in the right way
- 🪟 Strive for a culture of transparency

### How am I able to tell if we are not following it?

- You haven't proposed a refactoring that will enable your team to work safely.
- You've criticized other team members' proposals or requests without trying to understand their needs.
- You take too many risks that create situations that require heroic attitudes.
- You act defensively when someone points out that an attitude or implementation is not aligned with our principles.
- Team members seem afraid to share their opinions or give honest feedback.
