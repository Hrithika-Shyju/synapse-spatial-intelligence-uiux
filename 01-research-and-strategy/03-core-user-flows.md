# 03. Core User Flows

## 3.1 Overview

Core user flows describe the main interactions users perform while working with the Synapse Spatial Intelligence & Sensemaking Canvas.

The flows focus on three primary activities:

1. Data Ingestion and Entity Creation
2. Relationship Discovery and Sensemaking
3. Spatial Navigation and Investigation

These flows are designed to support investigative analysts in organizing information, exploring connections, and understanding complex networks of entities through an interactive spatial workspace.

---

## 3.2 Flow 1: Data Ingestion and Entity Creation

### Objective

Enable users to bring investigative information into the Synapse workspace and represent important information as visual entity nodes.

### User Flow

1. User opens the Synapse investigation workspace.
2. User selects the option to add or import information.
3. User provides the relevant investigative information through the available input method.
4. The information is reviewed and organized into identifiable entities.
5. User creates or adds entity nodes to the canvas.
6. Each node displays its primary identifying information.
7. User arranges the nodes within the investigation canvas.
8. User selects an individual node to inspect its contextual details.

### Flow Summary

**Open Workspace → Add Information → Review Information → Create Entity Nodes → Arrange Nodes → Inspect Entity**

### Expected Outcome

The user can organize investigative information as individual visual entities within a shared investigation canvas.

### Key UX Requirements

- Clear entry point for adding information.
- Recognizable visual representation for different entity types.
- Consistent node structure and hierarchy.
- Easy node placement and arrangement.
- Access to contextual entity information.

---

## 3.3 Flow 2: Relationship Discovery and Sensemaking

### Objective

Enable users to explore relationships between investigative entities and understand how different pieces of information are connected.

### User Flow

1. User opens an existing investigation canvas.
2. User identifies an entity that requires further exploration.
3. User selects the entity node.
4. User reviews its available contextual information.
5. User identifies another related entity.
6. User creates or examines a semantic relationship between the entities.
7. The relationship is represented visually through a connection between the nodes.
8. User continues exploring related entities and connections.
9. User organizes related entities into meaningful visual groups.
10. User reviews the resulting network to understand broader relationship patterns.

### Flow Summary

**Open Investigation → Select Entity → Inspect Details → Identify Related Entity → Explore Relationship → Connect Entities → Group Related Nodes → Review Network**

### Expected Outcome

The user can visually explore connections between people, organizations, transactions, communication records, and legal documents.

### Key UX Requirements

- Clear visual distinction between entities and relationships.
- Consistent relationship indicators.
- Easy selection of connected entities.
- Contextual information for selected nodes.
- Support for grouping related entities.
- Clear visualization of connected information.

---

## 3.4 Flow 3: Spatial Navigation and Investigation

### Objective

Enable users to navigate large investigation networks while maintaining context and switching between different levels of information.

### User Flow

1. User opens an investigation containing multiple entity nodes.
2. User views the current canvas layout.
3. User pans across the canvas to explore different areas.
4. User zooms in to inspect individual entities and their details.
5. The interface displays the Micro level of information.
6. User zooms out to view a broader set of entities and relationships.
7. The interface displays the Macro level of information.
8. User continues zooming out to examine larger clusters and network patterns.
9. The interface displays the Meta level of information.
10. User moves between the different zoom levels to explore the investigation.
11. User selects a relevant entity or cluster to continue the investigation.

### Flow Summary

**Open Canvas → Navigate Canvas → Zoom In → Micro View → Zoom Out → Macro View → Zoom Out → Meta View → Explore Clusters → Select Entity**

### Expected Outcome

The user can navigate large information networks and move between detailed entity inspection and high-level relationship exploration.

### Key UX Requirements

- Infinite canvas navigation.
- Smooth pan and zoom interactions.
- Consistent visual hierarchy across zoom levels.
- Readable entity information at different scales.
- Clear representation of clusters and network patterns.
- Preservation of investigation context during navigation.

---

## 3.5 Semantic Zoom Levels

Synapse uses three semantic zoom levels to adapt the amount of information displayed according to the user's current level of exploration.

### Micro Level

**Purpose:** Detailed entity inspection.

At the Micro level, users focus on individual entities and their available information.

**Displayed Information:**
- Entity name or identifier.
- Entity type.
- Important identifying details.
- Relevant metadata.
- Immediate relationship information.

**User Activity:** Inspecting individual entities and examining their details.

### Macro Level

**Purpose:** Relationship exploration.

At the Macro level, users view multiple entities and their immediate connections.

**Displayed Information:**
- Compact entity summaries.
- Connected entity nodes.
- Relationship indicators.
- Related entity groups.
- Important labels and categories.

**User Activity:** Exploring connections and understanding how entities relate to one another.

### Meta Level

**Purpose:** High-level network understanding.

At the Meta level, users examine broader structures and patterns across the investigation.

**Displayed Information:**
- Entity clusters.
- High-level network groupings.
- Major relationship patterns.
- Overview of connected information.
- Important areas of the investigation.

**User Activity:** Understanding the overall structure of the investigation and identifying areas for further exploration.

---

## 3.6 Core User Flow Summary

| User Flow | Primary Purpose | Main Interaction | Expected Outcome |
|---|---|---|---|
| Data Ingestion and Entity Creation | Add and organize investigative information | Adding information and creating nodes | Structured entity nodes on the canvas |
| Relationship Discovery and Sensemaking | Explore connections between entities | Selecting, connecting, and grouping nodes | Visual relationship network |
| Spatial Navigation and Investigation | Explore information at different scales | Pan, zoom, and select | Clear understanding of detailed and broader network information |

---

## 3.7 Overall User Journey

The three core flows work together to support the main Synapse investigation experience.

**Data Ingestion → Entity Creation → Relationship Discovery → Sensemaking → Spatial Navigation → Further Investigation**

The user begins by organizing information into entity nodes, explores relationships between those entities, and navigates the canvas to understand both individual details and broader network patterns.

This overall journey establishes the foundation for the information architecture, interaction design, and interface structure of Synapse.

---

## 3.8 UX Design Considerations

The following considerations should guide the design of the core user flows:

1. **Clarity:** Users should understand how to add, select, connect, and inspect entities.
2. **Consistency:** Interactions should behave consistently throughout the investigation workspace.
3. **Context Preservation:** Users should be able to inspect individual entities without losing their overall canvas position.
4. **Scalability:** The canvas should support investigations containing increasing numbers of entities and relationships.
5. **Visual Hierarchy:** Entity information should remain understandable across Micro, Macro, and Meta zoom levels.
6. **Efficient Navigation:** Users should be able to move through the canvas without unnecessary complexity.

These considerations will guide the development of Synapse's information architecture, interaction patterns, and high-fidelity prototype.

---

**Scope Note:** These flows describe the intended user experience and interaction design. Actual import formats, automated entity extraction, AI-assisted relationship discovery, and export functionality should only be included as implemented features if they are confirmed in the project scope.
