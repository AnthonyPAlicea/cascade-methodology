# Cascade Methodology: Software Development in the AI Age

## Definition

Cascade Methodology is an effort to leverage AI-Assisted Software Development in a modern SDLC, taking advantage of LLM benefits, and mitigating LLM risks.

Cascades are rapid AI-driven development cycles that flow from detailed specifications through interactive prototypes to production code, with verification gates that scale based on business risk tolerance.

To adopt Cascade Methodology means embracing and understanding both the benefits and the dangers of AI-assisted development, and using it to your greatest advantage.

For a long-form blog post on Cascade Methodology [see here](https://tonyalicea.dev/blog/cascade-methodology).

## Guiding Principles

Here are the 7 guiding principles of Cascade Methodology:
1. Understand the underlying user and business problems the software should solve.
1. Build the least amount of software possible to solve those problems.
1. Everyone has a seat at the table in writing specs.
1. Prototyping and user research are first-class citizens.
1. AI-generated code is not to be trusted.
1. The density of code quality checks needed to deploy code is a function of the entropy tolerance of the business process the code is supporting.
1. Scope and timelines are functions of entropy tolerance and understanding the problems to be solved.

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

### Definition
Entropy tolerance measures how much uncertainty a business process can safely accommodate from AI-generated solutions.

### Assessment Criteria
- **Impact of errors** on business operations
- **Regulatory requirements** and compliance needs
- **Data sensitivity** and privacy implications
- **User safety** and security considerations
- **Financial risk** exposure

### Verification Gate Types

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

This methodology serves teams seeking to harness AI capabilities responsibly while maintaining software quality and business risk management.
