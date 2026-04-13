# Evaluating Large Language Models as Strategic Assistants for Agile Product Owners

In this organization github users can found and reproduce the 


## Proposed Methodology
- Static evaluation :
  - Phase 1: Contextual Comprehension and Requirement Extraction.
  - Phase 2: Strategic Prioritization and Agile Alignment.
  - Phase 3: Phase 3: Architectural Viability and Implementation Assessment.
  - Phase 4: Code Quality, Security, and Technical Debt Inspection.
  - Phase 5: Consultative Maturity and Stakeholder Mediation.
- Dynamic Prototype Evaluation Protocol.
  
## PROMTS

- PROMPT 0:  Analyze the following base documents: the requirements specification and the technology stack in the form of a Dockerfile and a Docker-Compose.yml file.
- PROMPT 1:  Provide the user stories list obtained from the requirements specification. Identify the different types of requirements and their number. 
  - PROMPT 1a: Refer to the requirements specification file to identify which requirements should be included in the first sprint of this Scrum project. 
  - PROMPT 1b:  Indicate which requirements are included and the global percentage covered. 
  - PROMPT 1c:  Provide a justification for the unselected requirements from the perspective of the product owner. 
- PROMPT 2: Refer to the Docker-compose.yml file and create a full prototype for the first sprint of this Scrum project. Ensure you include all the detailed code and artefacts required for deployment.
- PROMPT 3: Indicate all the steps that need to be followed in order to present the prototype. 
- PROMPT 4: Perform a code analysis on the full prototype created and provide the relevant code metrics. 

## Replication repositories

- [RMOS - Restaurant Menu and Ordering System](https://github.com/SELab-ual/RMOS)
- ALI -  Amazing Lunch Indicator 
- Ecommerce - Online Bookstore 
- Camp - Summer Camp

