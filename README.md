# DITA_Learning
This repository provides insight into DITA, its core concepts and principles, and why it is important in technical documentation.
## What does DITA Stand for?
- **Darwin:** DITA uses the principles of inheritance for specialization
- **Information Typing:** DITA is designed for topic-based technical information based on an information architecture of concept, task, and reference
- **Architecture:** DITA provides the framework for the development of an Information Model
## What is DITA exactly?
An XML architecture and semantic markup language specifically designed by technical writers for creating structured, technical content.
## Why DITA?
- Industry-accepted architecture
- Open standards
- Active user community
- Topic-based approach
- Separation of form from content
- Meaningful, semantic tagging
- Conditional processing
- Indirect and direct referencing of content
- Inheritance of attributes and metadata
## What does the DITA model contain?
![DITA Model](dita_model.png)
## What does the DITA model contain?
![DITA Model includes](dita_model_include.png)
### What does the DITA model contain?
- A set of content units (elements)
  - Generic elements, valid in all information types
  - Information-type specific elements
  - Domain-specific elements
  - Book-specific elements
## What are content units?
- The core building blocks of the information types
- Semantic labels for the smallest chunks of information in your topic
- Containers for text, graphics, or other media
- Architectural files specify which are required and in what order for each information type
- Stylesheets specify how they are formatted
# Semantic vs syntactic markup
## Semantic
 - Describes what each element in a document is
 - Does not provide information on how to process those elements
 - Is used to structure your information
## Syntactic
 - Describes the format for processing text and images
 - Prepares content for presentation (web, paper, etc.)
### Syntactic markup example
**Example 1**
![Syntactic markup example 1](Syntax_markup_example.png)
**Example 2**
![Syntactic markup example 2](Syntax_markup_example1.png)
## Semantic labels
| Semantic | Syntactic |
|---|---|
| Task title | Heading 2 |
| Basic steps | Text box |
| Detailed step | Heading 3 |
|   - Instruction |  - Paragraph |
|   - Explaination | - Paragraph |
|   - Decision table | - Table |
|   - Example | - Graphic |
| Detailed step | - Graphic |
|   Instruction | Heading 3..|
# What does the DITA model contain?
## Blocked elements
- Common to all information types
  - Paragraphs
  - Lists
  - Notes
  - Tables
  - Figures
    
![Blocks](Block_elements.png)

- Information-type specific
  - Task: Context, Preresquisite, Steps, Postrequisite
  - Reference: Refsyn, Properties
  - Troubleshooting: Condition Cause, Remedy
    
![Note](Note.png)
![Terms](Terms.png)
## Inline elements
- Used within block elements
- Label words or phrases semantically
- May be related to a subject area or domain
  - User interface
  - Programming
  - Software
  - Highlighting

  ![Inline elements](Inline_elements.png)
