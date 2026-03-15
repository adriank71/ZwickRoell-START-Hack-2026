# ZwickRoell Case Development Framework

## 1. Topic of the Case
**GPT based data analytics**

## 2. Title of the Case
**Chat with your Test Data**

## 3. Case Summary

### A. What is the current problem?
ZwickRoell operates in the field of material testing laboratories, both in an R&D context and in series-accompanying quality assurance. Currently, it is very challenging to efficiently evaluate and interpret results from larger cohorts of material tests.

Traditional data scientists often lack the domain-specific expertise required to perform targeted and meaningful analyses. Conversely, material engineers and quality engineers possess the necessary domain knowledge but typically lack a strong background in statistical methods, data structures, and data interfaces.

As a result, the evaluation of large data cohorts becomes time-consuming, cumbersome, and inefficient. Furthermore, it is often difficult—if not impossible—to answer new questions based on historical test data if those questions were not anticipated at the time the tests were designed and conducted.

These limitations lead to inefficiencies and additional costs. More importantly, the full potential of testing data remains underutilized, for example in optimizing business processes or enabling well-founded, data-driven business decisions.

### B. What is the expected final product?
We envision an AI system that can be interacted with in natural language, enabling engineers in the material testing domain to work with it intuitively.

The AI system should:

- select the relevant data,
- prepare it if necessary,
- choose suitable algorithms,
- apply them to answer the user’s question as precisely as possible,
- return the result in natural language.

The system must also be able to explain each step transparently and in a way that is easy to follow. This may include graphical representations, with a focus on charts.

Typical questions may range from:

- simple selection tasks  
  - e.g. “List all data points or sets with property XYZ”
- comparative queries  
  - e.g. “Compare material or property A vs. B—are the differences statistically significant?”
- trend analyses  
  - e.g. “Is there an indication that boundary X will be violated in the future?”
- complex hypotheses  
  - e.g. “If I change parameter A, should that influence property B?”

These can involve multi-step analyses where intermediate results require selecting additional data and running further algorithmic processing.

#### Bonus
- **Reusability:** Users should be able to easily repeat or adapt queries, for example via recent queries, saved prompts, or templates, without starting from scratch every time.
- The system should provide clear, actionable answers and suggest recommended next steps, such as follow-up analyses or checks, with transparent reasoning and an auditable record.

### C. Who are the users of this solution?
- Material testing engineers
- R&D developers
- Laboratory managers
- Quality managers
- Production managers

## 4. Data
A data dump from a real-world testing lab scenario will be provided. It contains multiple measurement series from destructive material testing experiments, with a primary focus on tensile tests for metals and plastics.

In addition, the dataset includes:

- other test data, e.g. pendulum impact tests,
- measurements for some more exotic materials.

Participants are allowed to enrich the dataset with publicly available data wherever useful, provided this does not violate any legal or licensing restrictions.

## 5. Technology
The data will be provided in one of the following ways:

- as a **MongoDB dump** encapsulated in a Docker container with direct database-level access, or
- via **API-level access** (ideally REST), also packaged in a Docker image.

No specific LLM will be provided. Participants are completely free to choose:

- any LLM of their choice,
- any other AI tools they prefer.

## 6. Use Case and Business Case

### Advantages for users
- Efficiency and cost savings
- Faster information gathering
- Data-driven decision making

### Use case focus
Participants are encouraged to focus on one or more of the following scenarios:

- **Result validation and compliance**  
  - e.g. “Are these tests consistent with the relevant standard and our internal limits?”
- **Trend and drift analysis**  
  - e.g. “Is there a trend that tensile strength is decreasing over the last 6 months?”
- **Cross-machine / cross-site comparison**  
  - e.g. “How do Machine A and Machine B differ for this material?”

Participants are also welcome to identify and pursue other scenarios derived from the data that fit the **Chat with your Test Data** approach described above.

## 7. Judgment Criteria

### Creativity and Innovation (50%)
- Surprise effect to the jury
- Novelty of the concept
- Innovative application of AI to test data analysis

### Design (10%)
- Usability of the solution
- Clarity of the interface
- User-friendliness

### Viability and Feasibility (25%)
- Possibility of realizing the solution in practice
- Realistic implementation potential
- Suitability for real-world use

### Complexity and Technical Sophistication (15%)
- Usage of appropriate services and technologies
- Quality of the technical implementation
- Depth of the analytical workflow

## 8. Presentation Prototype

### Format
- Live demo strongly recommended (hands-on style showing real interaction)
- User-friendly slides (PDF, PPTX)
- Optional: Interactive UX prototype in Figma or similar tools to demonstrate interface and flows

### Key Elements
- **Solution representation:** Showcase the proposed application
- **Functional highlights:** Highlight the key functionalities of the application
- **Limitations:** Explain the technical limitations identified in the given context

### Requirements
- Conciseness
- Comprehensiveness
- Descriptions where necessary
- Executable software component for further testing and presentations to management
- Optional: UX prototype in Figma or similar software

## 9. Point of Contact
- **Sascha Meudt** — Head of Innovation Unit (IV3), primary point of contact

Not yet fully confirmed, but expected to be involved:
- **Sven Stamm** — Software Developer, Innovation Unit (IV3), point of contact for technology and data understanding
- **Shantanu Sonar** — Product Manager Digital Services (ZwickRoell)

Potential partial involvement, for example as jury members:
- **Vanessa Marks** — Team Lead Software Product Management & Data Analytics (ZwickRoell)
- **Bernadette Tonnier** — Innovation & Investment Management (IV3)

## 10. Prize
The winning team will be invited to visit ZwickRoell in **Ulm, Germany**.

During the visit, the team will:
- receive an exclusive tour of the headquarters,
- experience state-of-the-art material testing machines in action,
- enjoy lunch with members of the executive board.

Afterwards, the team will:
- climb the world’s tallest historic church tower and enjoy the view,
- walk through Ulm’s charming and picturesque old town,
- end the day with a special dinner to celebrate their success.
