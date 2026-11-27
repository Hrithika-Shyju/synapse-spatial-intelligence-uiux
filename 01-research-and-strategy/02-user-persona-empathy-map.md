# 02. User Persona & Empathy Map

## 2.1 Overview

The purpose of this section is to understand the target users of Synapse, their goals, motivations, workflows, frustrations, and information needs.

Synapse is designed for investigators and intelligence analysts who need to examine information from multiple sources, identify relationships between entities, and make sense of complex networks of information.

Understanding these users helps guide the platform's interface structure, navigation, interaction design, and overall user experience.

## 2.2 Primary User Persona

### Persona: Investigative Analyst

**Name:** Alex Morgan (Representative persona)  
**Role:** Investigative Analyst  
**Experience:** Experienced in reviewing and organizing investigative information  
**Primary Tool:** Digital investigation and information analysis tools  
**Technical Comfort:** Comfortable using digital tools to examine and organize information.

### Background

Alex is an investigative analyst who works with information collected from different sources, including records, documents, communication data, and organizational information.

The role involves reviewing individual pieces of information, identifying possible connections, and organizing findings into a clear structure.

When information is spread across multiple documents and tools, understanding how different entities relate to one another becomes difficult. Alex needs a workspace that makes it easier to explore information visually while maintaining the context of the investigation.

### Goals

- Organize information from multiple investigative sources in one workspace.
- Identify relationships between people, organizations, transactions, and documents.
- Understand complex networks of connected entities.
- Explore individual entities without losing the overall investigation context.
- Navigate large amounts of information efficiently.
- Build a clear visual representation of investigative findings.

### Motivations

- Reduce the effort required to organize fragmented information.
- Discover meaningful connections between different entities.
- Maintain a clear overview of the investigation.
- Move easily between detailed information and broader relationship patterns.
- Improve the clarity and structure of investigative workflows.

### Frustrations

- Information is scattered across multiple sources and documents.
- Manually mapping relationships can be time-consuming.
- Large amounts of information make important connections difficult to notice.
- Switching between tools interrupts the investigation workflow.
- Complex networks become difficult to navigate and understand.
- Viewing detailed information can make it harder to maintain an overall perspective.

### Needs

- A unified workspace for investigative information.
- Clear visual representation of entities and their relationships.
- Easy ways to add, arrange, and connect entity nodes.
- Contextual details for selected entities.
- Flexible canvas navigation through pan and zoom.
- Multiple levels of information visibility through semantic zoom.
- A clear way to group and explore related entities.

## 2.3 User Workflow

The following workflow represents a proposed investigation process that Synapse aims to support.

### Step 1: Collect Information

The analyst gathers relevant information from available investigative sources, such as documents, records, and communication data.

**User need:** A consistent way to bring relevant information into the investigation workspace.

### Step 2: Organize Entities

The analyst identifies important entities such as people, organizations, transactions, and documents.

**User need:** A structured visual representation of different entity types.

### Step 3: Explore Relationships

The analyst examines how different entities are connected and organizes those relationships visually.

**User need:** Clear semantic connections between related entities.

### Step 4: Investigate Details

The analyst selects individual entities to examine their associated information and relationships.

**User need:** Contextual information without losing the overall canvas view.

### Step 5: Understand the Bigger Picture

The analyst zooms out to examine groups of connected entities and broader relationship patterns.

**User need:** Multiple levels of visual detail to support both focused and high-level exploration.

## 2.4 Empathy Map

The empathy map describes the proposed thoughts, feelings, observations, and actions of the investigative analyst while working with complex information.

### SAYS

- "I need all the relevant information in one place."
- "I want to understand how these entities are connected."
- "It is difficult to keep track of all these relationships."
- "I need to see the details without losing the bigger picture."

### THINKS

- Which entities are important to this investigation?
- How are these people, organizations, and records connected?
- Am I missing any relevant relationships?
- How can I organize this information more clearly?
- How can I move between detailed information and the overall network?

### DOES

- Reviews information from multiple sources.
- Identifies important entities and records.
- Organizes information into categories.
- Examines connections between entities.
- Moves between individual records and broader information structures.
- Revisits previously identified information to understand its context.

### FEELS

- Overwhelmed when information is scattered across multiple sources.
- Frustrated when relationships are difficult to track.
- Concerned about losing important context.
- More confident when information is clearly organized.
- Focused when connections can be explored visually.

## 2.5 Key User Pain Points

| Pain Point | Description | Design Opportunity |
|---|---|---|
| Fragmented information | Information is distributed across different sources. | Provide a unified investigation canvas. |
| Manual organization | Entities and relationships require manual organization. | Support visual entity creation and arrangement. |
| Complex relationships | Connections between multiple entities are difficult to understand. | Use semantic links and relationship visualization. |
| Information overload | Large networks can become visually overwhelming. | Introduce semantic zoom and entity grouping. |
| Loss of context | Examining individual details can disconnect users from the overall investigation. | Provide contextual inspection while preserving canvas visibility. |
| Navigation difficulty | Large information networks are difficult to explore. | Provide infinite canvas navigation with pan and zoom. |

## 2.6 Design Opportunities

Based on the proposed persona, workflow, and empathy map, the following design opportunities are identified:

1. **Unified Investigation Workspace:** Create a central canvas where different types of investigative information can be organized.

2. **Entity-Based Visualization:** Represent people, organizations, transactions, communication records, and legal documents as identifiable nodes.

3. **Semantic Relationship Mapping:** Allow users to understand how entities are connected through visual relationship links.

4. **Contextual Entity Inspection:** Provide additional information about selected entities without interrupting the overall workspace.

5. **Semantic Zoom:** Support three levels of exploration:
   - **Micro:** Detailed view of individual entities and their information.
   - **Macro:** Compact view of entities and their immediate relationships.
   - **Meta:** High-level view of clusters and broader network patterns.

6. **Flexible Canvas Navigation:** Enable users to move around large investigation networks through pan and zoom interactions.

7. **Visual Organization:** Support grouping and arranging related entities to improve clarity.

## 2.7 Key UX Takeaways

The persona and empathy map highlight several important UX requirements for Synapse:

- The interface should make complex information easier to understand.
- Entity relationships should be visually clear and distinguishable.
- Users should be able to inspect details without losing their position in the investigation.
- The canvas should support both detailed exploration and high-level analysis.
- Navigation should remain consistent as the investigation grows.
- Visual organization should help users maintain context and reduce information overload.

These findings will guide the information architecture, interaction design, and visual design decisions in the next stages of the Synapse project.

---

**Research Note:** This persona and empathy map are initial design assumptions based on the intended Synapse use case. They should be validated and refined through mentor feedback, stakeholder discussions, or user interviews.
