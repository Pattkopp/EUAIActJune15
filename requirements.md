## Methodology.

1. **Identifying requirements.**

   1. We search through the [adopted](https://www.europarl.europa.eu/doceo/document/TA-9-2023-0236_EN.html) [AI Act draft](https://www.europarl.europa.eu/doceo/document/TA-9-2023-0236_EN.pdf) from EU Parliament for “foundation model” and related terms. We list any requirements directed towards foundation model providers, which are concentrated in Article 28b and Annex VIII.
   2. To ensure completeness, we list requirements referenced in the sections on foundation model providers: these requirements are more general, but do apply to foundation model providers. We then read the document sequentially over all 349 pages, adding any final requirements.
   3. To be clear, we provide the exact language + position from the AI Act draft.

2. **Filtering requirements.** Having identified 20 requirements, we remove any requirements that do not make sense.

   1. **Ill-defined prior to AI Act (5).** Registry, pre-market compliance, quality management, law-abiding content, appropriate levels: These requirements perhaps could be assessed, but make more sense once the AI Act is in place.
   2. **Trivial (2).** Provider name and model name are already addressed and non-substantive in the settings we consider.
   3. **Too early (1)**. The upkeep requirement not only makes more sense once the AI is in place, but also specifies a period of 10 years that is much longer than the current history of foundation models.
   4. **Superseded (1).** The general principles requirement is itself covered by the other requirements for foundation models.
   5. **Overlap (1).** The requirements for machine-generated content and awareness of interacting with AI systems are quite related, so we do not separate them at this point, pending further clarification/finalization of the proposed law.

3. **Designing rubrics.** For each of the 12 requirements we evaluate, we specify a 5-point rubric.


## Requirements.

1. **Registry** \[Article 39, item 69, page 8 as well as Article 28b, paragraph 2g, page 40]. In order to facilitate the work of the Commission and the Member States in the artificial intelligence field as well as to increase the transparency towards the public, providers of high-risk AI systems other than those related to products falling within the scope of relevant existing Union harmonization legislation, should be required to register their high-risk AI system and foundation models in a EU database, to be established and managed by the Commission. This database should be freely and publicly accessible, easily understandable and machine-readable. The database should also be user friendly and easily navigable, with search functionalities at minimum allowing the general public to search the database for specific high-risk systems, locations, categories of risk under Annex IV and keywords. Deployers who are public authorities or European Union institutions, bodies, offices and agencies or deployers
2. **Provider name** \[Annex VIII, Section C, page 24]. Name, address and contact details of the provider.
3. **Model name** \[Annex VIII, Section C, page 24]. Trade name and any additional unambiguous reference allowing the identification of the foundation model.
4. **Data sources** \[Annex VIII, Section C, page 24]. Description of the data sources used in the development of the foundation model.
5. **Capabilities and limitations** \[Annex VIII, Section C, page 24]. Description of the capabilities and limitations of the foundation model.
6. **Risks and mitigations** \[Annex VIII, Section C, page 24 and Article 28b, paragraph 2a, page 39]. The reasonably foreseeable risks and the measures that have been taken to mitigate them as well as remaining non-mitigated risks with an explanation on the reason why they cannot be mitigated.
7. **Compute** \[Annex VIII, Section C, page 24]. Description of the training resources used by the foundation model including computing power required, training time, and other relevant information related to the size and power of the model.
8. **Evaluations** \[Annex VIII, Section C, page 24 as well as Article 28b, paragraph 2c, page 39]. Description of the model’s performance, including on public benchmarks or state of the art industry benchmarks.
9. **Testing** \[Annex VIII, Section C, page 24 as well as Article 28b, paragraph 2c, page 39]. Description of the results of relevant internal and external testing and optimisation of the model.
10. **Member states** \[Annex VIII, Section C, page 24]. Member States in which the foundation model is or has been placed on the market, put into service or made available in the Union.
11. **Downstream documentation** \[Annex VIII, 60g, page 29 as well as Article 28b, paragraph 2e, page 40]. Also, foundation models should have information obligations and prepare all necessary technical documentation for potential downstream providers to be able to comply with their obligations under this Regulation.
12. **Machine-generated content** \[Annex VIII, 60g, page 29]. Generative foundation models should ensure transparency about the fact the content is generated by an AI system, not by humans.
13. **Pre-market compliance** \[Article 28b, paragraph 1, page 39]. A provider of a foundation model shall, prior to making it available on the market or putting it into service, ensure that it is compliant with the requirements set out in this Article, regardless of whether it is provided as a standalone model or embedded in an AI system or a product, or provided under free and open source licenses, as a service, as well as other distribution channels.
14. **Data governance** \[Article 28b, paragraph 2b, page 39]. Process and incorporate only datasets that are subject to appropriate data governance measures for foundation models, in particular measures to examine the suitability of the data sources and possible biases and appropriate mitigation.
15. **Energy** \[Article 28b, paragraph 2d, page 40]. Design and develop the foundation model, making use of applicable standards to reduce energy use, resource use and waste, as well as to increase energy efficiency, and the overall efficiency of the system. This shall be without prejudice to relevant existing Union and national law and this obligation shall not apply before the standards referred to in Article 40 are published. They shall be designed with capabilities enabling the measurement and logging of the consumption of energy and resources, and, where technically feasible, other environmental impact the deployment and use of the systems may have over their entire lifecycle.
16. **Quality management** \[Article 28b, paragraph 2f, page 40]. Establish a quality management system to ensure and document compliance with this Article, with the possibility to experiment in fulfilling this requirement.
17. **Upkeep** \[Article 28b, paragraph 3, page 40]. Providers of foundation models shall, for a period ending 10 years after their foundation models have been placed on the market or put into service, keep the technical documentation referred to in paragraph 1(c) at the disposal of the national competent authorities.
18. **Law-abiding generated content** \[Article 28b, paragraph 4b, page 40]. Train, and where applicable, design and develop the foundation model in such a way as to ensure adequate safeguards against the generation of content in breach of Union law in line with the generally acknowledged state of the art, and without prejudice to fundamental rights, including the freedom of expression.
19. **Training on copyrighted data** \[Article 28b, paragraph 4c, page 40]. Without prejudice to national or Union legislation on copyright, document and make publicly available a sufficiently detailed summary of the use of training data protected under copyright law.
20. **Adherence to general principles** \[Article 4a, paragraph 1, page 142-3]. All operators falling under this Regulation shall make their best efforts to develop and use AI systems or foundation models in accordance with the following general principles establishing a high-level framework that promotes a coherent humancentric European approach to ethical and trustworthy Artificial Intelligence, which is fully in line with the Charter as well as the values on which the Union is founded: a) ‘human agency and oversight’ means that AI systems shall be developed and used as a tool that serves people, respects human dignity and personal autonomy, and that is functioning in a way that can be appropriately controlled and overseen by humans. b) ‘technical robustness and safety’ means that AI systems shall be developed and used in a way to minimize unintended and unexpected harm as well as being robust in case of unintended problems and being resilient against attempts to alter the use or performance of the AI system so as to allow unlawful use by malicious third parties. c) ‘privacy and data governance’ means that AI systems shall be developed and used in compliance with existing privacy and data protection rules, while processing data that meets high standards in terms of quality and integrity. d) ‘transparency’ means that AI systems shall be developed and used in a way that allows appropriate traceability and explainability, while making humans aware that they communicate or interact with an AI system as well as duly informing users of the capabilities and limitations of that AI system and affected persons about their rights. e) ‘diversity, non-discrimination and fairness’ means that AI systems shall be developed and used in a way that includes diverse actors and promotes equal access, gender equality and cultural diversity, while avoiding discriminatory impacts and unfair biases that are prohibited by Union or national law. f) ‘social and environmental well-being’ means that AI systems shall be developed and used in a sustainable and environmentally friendly manner as well as in a way to benefit all human beings, while monitoring and assessing the long-term impacts on the individual, society and democracy. For foundation models, the general principles are translated into and complied with by providers by means of the requirements set out in Articles 28 to 28b.
21. **System is designed so users know its an AI** \[Article 52(1) [Paragraph](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=celex%3A52021PC0206) 1 - not in the Compromise text, but invoked in 28(b), paragraph 4a, page 40]. Providers shall ensure that AI systems intended to interact with natural persons are designed and developed in such a way that natural persons are informed that they are interacting with an AI system, unless this is obvious from the circumstances and the context of use. This obligation shall not apply to AI systems authorised by law to detect, prevent, investigate and prosecute criminal offences, unless those systems are available for the public to report a criminal offence.
22. **Appropriate levels** \[Article 28b, paragraph 2c, page 39]. design and develop the foundation model in order to achieve throughout its lifecycle appropriate levels of performance, predictability, interpretability, corrigibility, safety and cybersecurity assessed through appropriate methods such as model evaluation with the involvement of independent experts, documented analysis, and extensive testing during conceptualisation, design, and development