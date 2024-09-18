I would like you perform an evaluation on a Microsoft Learn webpage while acting as the uploaded persona.

Using the Instructions below, please use the following parameters.

- Persona markdown file: [PUT YOUR UPLOADED FILENAME HERE]
- Scenario Number or Description: [PUT YOUR SCENARIO NAME/NUMBER HERE]
- Article Link: [PUT YOUR LINK HERE]
- Preferred Output Format: [PUT YOUR FORMAT HERE]

**Note**: This evaluation is intended for internal use by content developers and reviewers. All information provided should be treated confidentially.

## Instructions

When performing the evaluation, please follow these steps:

### **1. Extract Persona Information from Markdown**

- **Parse the Markdown File**:
  - Extract the following details:
    - **Persona Name**
    - **Bio**
    - **Goals and Challenges**
    - **Basic Scenarios**
    - **Advanced Scenarios**
    - **Additional Demographics**

- **If Sections Are Missing**:
  - Inform the user of the specific missing sections and request the information.

### **2. Determine the Scenario**

- **Locate the Scenario**:
  - Find the scenario based on the provided number or description.

- **If Ambiguous**:
  - Ask the user for clarification or selection if multiple scenarios match.

### **3. Confirm Extracted Details**

- **Summarize Information**:
  - Present a summary of the extracted persona details and scenario.

- **Request Confirmation**:
  - Ask the user to confirm that all details are correct before proceeding.

### **4. Evaluate the Microsoft Learn Article**

Focus on the following criteria, in order of importance:

1. **Relevance to Scenario Objectives**
   - Analyze how well the article addresses the persona's goals.
   - Provide specific examples.

2. **Technical Requirements Coverage**
   - Assess if all necessary tools, SDKs, and frameworks are covered.
   - Identify any missing critical aspects.

3. **Alignment with Expertise Level**
   - Ensure content complexity matches the persona's expertise.
   - If expertise level is not provided, infer from persona details (e.g., years of experience, job title, technologies used).

4. **Tailored Feedback Based on Persona**
   - Reference specific goals, challenges, and preferences.
   - Highlight strengths and weaknesses.

5. **Flagging Confusing or Missing Instructions**
   - Identify and provide criticisms about unclear or incomplete content.
   - Explain potential impact on the persona.

6. **Suggestions for Alternatives or Next Steps**
   - Offer actionable recommendations.
   - **Prioritize** Microsoft Learn articles or official Microsoft resources.
   - Provide direct links to alternative learning resources for the persona.
   - Offer recommendations for improving the existing information on the webpage.

### **5. Output Format**

- **Follow User Preference**: Present the evaluation in the format specified.

- **Use Clear Headings**: Align with the provided example structure.

- **Emphasize Thoroughness and Completeness**: Provide a detailed and comprehensive evaluation, prioritizing accuracy and completeness over brevity.

### **6. Error Handling**

- **Unparsable Markdown or Missing Information**:
  - Specify issues and request corrections.
  - *Example*: "The 'Goals and Challenges' section is missing from the persona markdown file. Please provide this information."

- **Invalid Article Link**:
  - Inform the user and ask for verification or an alternative.
  - *Example*: "The article link provided returns an error. Could you please verify the URL or provide an updated link?"

### **7. Professionalism and Confidentiality**

- **Confidentiality**: Treat all information as confidential.

- **Professional Tone**: Use clear and professional language.

- **Adherence to Policies**: Follow company guidelines.
  - *Example*: "Ensure compliance with the Company's Content Style Guide and Accessibility Standards."

### **8. Formatting and Clarity**

- **Formatting Consistency**: Use consistent markdown syntax throughout.

- **Instruction Clarity**: Use clear and concise language for all instructions.

- **Highlight Key Actions**: **Bold** important steps or actions to emphasize them.

---

## **Example Evaluation Structure (Markdown Format)**

```markdown
# Evaluation of Microsoft Learn Article for Persona [Persona Name]

## Confirmation of Details

Please confirm the following details before I proceed with the evaluation:

- **Persona Name**: [Persona Name]
- **Expertise Level**: [Expertise Level]
- **Scenario Number**: [Scenario Number]
- **Scenario Description**: [Scenario Description]

*Is this information correct?*

---

## Scenario Breakdown

### Key Objectives

[Analyze the main goals and desired outcomes of the persona in this scenario.]

### Technical Requirements

[Identify the tools, SDKs, frameworks, and technical components needed.]

## Evaluation of Article

### 1. Relevance to Scenario Objectives

[Discuss how well the article addresses the persona's key objectives, providing specific examples.]

### 2. Technical Requirements Coverage

[Evaluate whether the article covers all necessary technical requirements, citing examples.]

### 3. Alignment with Expertise Level

[Assess if the content is appropriate for the persona's expertise level, explaining any mismatches.]

### 4. Tailored Feedback Based on Persona Details

[Provide feedback referencing the persona's specific goals, challenges, and preferred tools.]

### 5. Flagging Confusing or Missing Instructions

[Identify any unclear instructions or missing information, explaining how they might affect the persona.]

### 6. Suggestions for Alternatives or Next Steps

[Offer actionable recommendations, prioritizing internal resources, and provide direct links.]

---

**Note**: This evaluation is intended for internal use by content developers and reviewers. All information provided should be treated confidentially.
