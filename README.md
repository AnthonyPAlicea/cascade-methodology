# Cascade Methodology: Software Development in the AI Age

## Definition

Cascade Methodology is replacement for software development methodologies like Agile and Waterfall in the age of AI. It is designed to leverage AI-Assisted Software Development in a modern SDLC, taking advantage of LLM benefits, and mitigating LLM risks.

Cascades are rapid AI-driven development cycles that flow from detailed specifications through interactive prototypes to production code, with verification gates that scale based on business risk (entropy) tolerance.

It includes concepts such as Minimum Solved Problems (MSP), a problem-focused replacement for MVP, LLM-generated prototypes and user research as first-class citizens, and an awareness at all levels that AI requires good context to generate useful code, but at the same time that code can never be truly trusted.

To adopt Cascade Methodology means embracing and understanding both the benefits and the dangers of AI-assisted development, and using it to your greatest advantage.

## Learn More
- [Blog post on Cascade Methodology](https://tonyalicea.dev/blog/cascade-methodology) - a long-form introduction. 
- [Blog post on the 'Why Down' method and MSP](https://tonyalicea.dev/blog/on-the-why-down/)
- [Blog post on Entropy Tolerance](https://tonyalicea.dev/blog/entropy-tolerance-ai/)  
- [Book draft](./book) - being written in the open here in this repo.  
- [Work with Tony Alicea](https://tonyalicea.dev/work-with-me/) - inquiries about workshops, consultation, and education.  

## Discuss
- Discuss implementing Cascade Methodology with others [here in this repo](https://github.com/AnthonyPAlicea/cascade-methodology/discussions).

## Guiding Principles

Here are the 7 guiding principles of Cascade Methodology:
1. Everyone has a seat at the table in writing specs.  
2. Understand the underlying user and business problems the software should solve.  
3. Build the least amount of software possible to solve those problems.  
4. Prototyping and user research are first-class citizens.  
5. AI-generated code is not to be trusted.  
6. The density of code quality checks needed to deploy code is a function of the entropy tolerance of the business process the code is supporting.  
7. Scope and timelines are functions of entropy tolerance and understanding the problems to be solved.

## The Cascade Structure

A cascade is a complete development cycle from specification to deployment, consisting of five phases:

```
1. SPEC ←──────────────┐
   ↓                   │
2. EXPERIMENT ─────────┘
   ↓
3. IMPLEMENT ←─────┐
   ↓               │
4. VERIFY ─────────┘
   [porous or dense]
   ↓
5. DEPLOY
```

### Phase 1: Specification
Creation of detailed requirements that serve as both human documentation and AI context. Specifications are hypotheses about user needs and technical solutions.

### Phase 2: Experiment
AI-generated interactive prototypes enable rapid user research, stakeholder validation, and technical feasibility assessment. Experimentation may iterate back to specification refinement.

### Phase 3: Implementation
Production code generation using specification and experimental findings as context. AI implements validated designs with human oversight.

### Phase 4: Verification
Risk-appropriate quality assurance based on the entropy tolerance of the supported business process. Verification gates range from porous (basic functionality) to dense (comprehensive security and compliance review).

### Phase 5: Deployment
Release of verified code through established deployment pipelines. Teams should implement Verified Integration / Continuous Deployment (VI/CD), where only code that passes entropy-appropriate verification gates is integrated and deployed.

## Entropy Tolerance Framework
Recognizing that AI code is fundamentally untrustworthy requires a metric to then safely determine the dangers of 'vibe coding' a feature.

### Definition
Entropy tolerance measures how much uncertainty a business process can safely accommodate from AI-generated solutions.

### Assessment Criteria
- **Impact of errors** on business operations
- **Regulatory requirements** and compliance needs
- **Data sensitivity** and privacy implications
- **User safety** and security considerations
- **Financial risk** exposure

### Verification Gate Types
Generated code requires a degree of verification relative to the entropy tolerance of the underlying process the code is supporting.

**Porous Gates** (High Entropy Tolerance)
- Marketing content and visual elements
- Internal tools and dashboards
- Experimental features
- Non-critical user interface components

**Medium Gates** (Medium Entropy Tolerance)
- Performance-sensitive components
- Customer support ticket routing and responses
- Product recommendation engines
- User onboarding workflows

**Dense Gates** (Low Entropy Tolerance)
- Financial transaction processing
- Personal data handling systems
- Security and authentication mechanisms
- Regulatory compliance features
- Safety-critical functionality

## Organizational Adoption
Shifting organizational culture where needed is a challenge of it's own, so Cascade Methodology includes recommendations on how to accomplish it.

Here are some culture and support goals to successfully implement the methodology:

### Cultural Requirements
- Embrace "problems to be solved" (MSP) over features (MVP)
- Embrace iterative specification refinement
- Value experimentation and user research
- Accept AI collaboration with appropriate skepticism

### Prerequisites
- AI development tool integration
- User research capabilities
- Risk assessment frameworks
- Flexible verification processes

## Conclusion
Cascade Methodology recognizes that large language models fundamentally change software development economics. By structuring development around AI strengths while mitigating AI risks through entropy-scaled verification, teams can achieve both higher learning velocity and appropriate quality assurance.

Cascades serve teams seeking to harness AI capabilities responsibly while maintaining software quality and business risk management.
