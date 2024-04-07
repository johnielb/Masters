# Revisiting the Algorithm Charter

Johniel Bocacao

April 2024

## 1. Introduction

Government agencies employ algorithms to enhance their delivery of services to New Zealand citizens. 

- Importance of getting it right for government who has a monopoly on a variety of services: social welfare, legal violence (police), entry to the country.
- Examples of uses, something using minor business rules, something complex uplifting, something complex punishing. 
- Use of personal data to train. 
- Can lose social license if they are misusing data, jumping the gun and creating models without understanding, perpetuate bias against communities. 
- Solve this issue by putting up safeguards to ensure they use data appropriately and know what's going on. 
- Effectively communicate this knowledge to the public. 

Set the scene, why I am doing this. Triangulate based on unique insight I have at ACC.

- Government agencies collect data on citizens that interact with it, use that data for algorithms to improve service delivery, target, predict etc. 
- Government agencies need to have safeguards in place to ensure they use data for algorithms appropriately, ethically, with social license.
- Algorithm Charter developed to commit agencies to basic principles around transparency, accountability, and considerations during the algorithm lifecycle.
- Agencies embed principles in their enterprise policies to truly take effect
- Year 1 review commissioned by StatsNZ in 2021 focused on operationalisation rather than a thorough, first principles review

### 1.1. Motivation

At the lowest level of the algorithm development process, the Algorithm Charter requires that "data is fit for purpose by understanding its limitations [and] identifying and managing bias". While this consideration will already be part of the processes of agencies with mature algorithm development capability, there is a case for providing further guidance in operationalising this principle:

- A standard set of fitness measures, both for the data and the algorithm where applicable, provides a consistent benchmark to readily assure stakeholders (from internal governance advisors to the general public) that an algorithm is fit for purpose.
- A gold standard for measuring fitness can help agencies early in their algorithm maturity to embed best practices during model development and governance.
- Clarifying the importance for monitoring algorithms on an ongoing basis can ensure the data and algorithm continues to be fit for purpose and bias is managed. 
- Quantifying bias and fairness is complex issue. Methodologies and tools 
- 
- [Discuss fairness and bias. Tradeoffs between different types of fair such as equity vs , complex philosophical problem that agencies definitely need guidance to grapple].

People and partnership. Segue from talking about biases. Difficult to engage communities as they often don't have the capability to discuss. Information asymmetry, without guidance may lead to mistaken concerns, wrong questions being asked, leading to a worse position, making decisions that lead to worse models. What is the right level of engagement with communities, particularly priority communities like Māori who have Treaty rights to have a say in how decisions made about them are made.

Algorithm specific advice on PHRAE.

Investigate the human oversight principle. Are operators falling to automation bias? How is this verified when there aren't hard controls in place, i.e. trust that the human is reviewing decisions. How the role of humans in automated decisions to mitigate any impact

Linking all motivations is how agencies make these considerations transparent. Different users will need different information: developers as models are refined and monitored, general public, 'gatekeepers' like internal governance bodies, risk managers, priority communities.

Reported difficulty in understanding what’s in scope of 'algorithm'. Where does GenAI fit?

### 1.2. Research Objectives

Critical analysis looking at the algorithm lifecycle more generally across agencies - critique each step of the way from all perspectives: how developers operationalise Charter considerations (both pre and post prod: data fit for purpose, human oversight, PHRAE), how developers seek approval from gatekeepers, how organisations engage affected communities, how organisations monitor and manage risk on an ongoing basis. [First principles review of the Charter? Do we need to go wider? Maybe a different Generative Algorithm Charter to define expectations when agencies e.g. refine a foundational model for specific purposes.]

Second stage will develop solution(s) that fill identified gaps, solve these problems. [Identify must/should/could measures for monitoring algorithms]. [Both quantitative and qualitative for managing soft risk, both conventional data sci measures and ones called by Charter (human oversight, people, partnership)]. [Provide guidance on complex issues like quantifying bias].

[As seamless as possible, integrate into existing data science pipelines]. [Consistent pattern general enough to apply to all agencies, modular enough that measures that may not apply to a problem can be explained away]. [Omission of this regular, seamlessly produced artefact can easily call into question an agency's commitment to transparency]. [So easy that inability to produce the artefact will call into question an agency's ability to explain a model, let alone observe or monitor it]. 

[Flexible enough that it can serve mutliple audiences]. [Data scientists to compare model options, performance/compliance]. [Communities to guide their discussions around what an algorithm means for them, how it performs for them vs others/all]. [Gatekeepers to provide a framework around discussions when evaluating compliance]. [General public to easily understand that government uses their data, runs algorithms appropriately through a publicly accessible, central register].

## 2. Background

### 2.1. Algorithms in the Public Sector

- Define what’s in scope of AC
- Examples of algorithms, what’s not an algorithm
- Generative AI - pending question
- Interim Generative AI guidelines for NZ Government but only for services - not for GAI dev itself.

### 2.2. Measuring Algorithmic Fitness

- Specific guidance will help agencies identify and mitigate the risk of data drift: when the underlying structure of fresh input data changes as the algorithm remains constant; and concept drift: when the relationship between the input data and the decision changes. 
- Fairness and bias.
    - Modify data before trianing
    - Modify algorithm trained
    - Modify predictions of model
    - Root cause analysis, e.g. 

### 2.3. Algorithm Charter of Aotearoa New Zealand

- History and development, who did Stats interview
- Find suggestions from submissions made 
- Year 1 review, parameters, limitations.
    - Interviews from agencies with high-risk algorithms
    - Interviews with civil society: academics, peak bodies, MDS/Tiriti experts
    - Questionnaires to analytics Tier 2s, non-signatory agencies.
    - Agencies were excluded on the basis of minimal use of algorithms.
    - Out of scope: amendments, private sector, **outcomes**.
- Outstanding and actioned recommendations from the Year 1 review

### 2.4. Related Regulation

Regulation for the purposes of this research comprises of hard levers of setting the rules. Legislation

#### 2.4.1. Official Information Act

Freedom of information around government decision making. Is it

#### 2.4.2. Privacy Act

Comply with information privacy principles. Make available any information an agency holds on a requesting individual.

### 2.5. Related Frameworks

Frameworks are softer levers for setting rules, usually within an agency or a community of agencies that 

#### 2.5.1. Algorithm Impact Assessment

Drafted as a result of Year 1 review for assessing algorithm risk at the pre-deployment phase, including whether it is high risk enough to fall under the Charter.

#### 2.5.2. Internal Agency Frameworks

- PHRAE - MSD impact-side evaluation prior to deployment
- MDL - MSD framework for model development and maintenance
- DPUP - SWA
- StatsNZ IDI - Nga Tikanga Paihere. Stats framework for applying tikanga Māori to data use

#### 2.5.3. Māori Algorithmic Sovereignty

As per *(Brown et al., 2023)*, how they were transformed from MDS principles already circulated to agencies.

### 2.6. Related Efforts

#### 2.6.1. Centre for Data Ethics and Innovation

#### 2.6.2. Algorithm Transparency in Open Government Partnership 

Probably where we talk about public participation, IAP2 Spectrum.

### 2.7. Related International Efforts

- Canadian directives on responsible AI
- Apply EU AI Act ideas in a non-commercial context
- Biden administration EO, guidance to federal agencies on AI use

## 3. Timeline

|                  | 2       | 3 | 4      | 5        | 6 | 7 | 8 | 9       | 10 | 11 | 12 |
| ---------------- | ------- | - | ------ | -------- | - | - | - | ------- | -- | -- | -- |
| Analysis         | Lit rev | X | X      | Analysis | X |   |   |         |    |    |    |
| Interview dev    |         | X |        |          |   |   | X |         |    |    |    |
| Primary research |         |   | Discov | X        |   |   |   | Testing | X  |    |    |
| Ideation         |         |   |        | X        | X |   |   |         | X  | X  |    |
| Solution devt    |         |   |        |          | X | X | X |         |    | X  | X  |
<p align = "center">Table 1 - Proposed Gantt chart (column represents 2 months)</p>


### 3.1. Critical Analysis (10 months)

Critical analysis of the state of play across the breadth of the Charter? Frame as not just a review but a contribution in its own right

#### 3.1.1. Interview development (2 months)

Write up questions and script, devise sample

#### 3.1.2. Primary research (4 months)

Undertake interviews

#### 3.1.3. Ideation and Synthesis (overlapping 4 months)

Integrate learnings from research

### 3.2. Solution development (overlapping 14 months)

Similar waterfall structure: develop tool, devise and perform user tests, integrate feedback, finalise solution. This may be around quantification of bias, developing a model register API/framework around what measures/stats needs to be published.

## 4. Resources

### 4.1. Interview Participants

Who is in and out of scope for interviewing, how I’ll build a representative sample. Ethical considerations.

### 4.2. Trial Data for Solution Development

What data I’ll be using to test solutions

# Bibliography

Brown, P. T., Wilson, D., West, K., Escott, K. R., Basabas, K., Ritchie, B., Lucas, D., Taia, I., Kusabs, N. & Keegan, T. T.. (2023). Māori algorithmic sovereignty: idea, principles, and use. arXiv:2311.15473


