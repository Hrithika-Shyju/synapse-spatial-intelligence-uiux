# 04. Information Architecture & Spatial Rules

## 4.1 Overview

Information Architecture (IA) defines how the different sections, tools, and information elements of Synapse are organized.

Synapse uses a spatial, node-based interface that allows investigative analysts to organize entities, explore relationships, and navigate complex information through an infinite canvas.

The workspace is structured around five primary interface zones:

1. Investigation Sidebar
2. Top Navigation Bar
3. Infinite Investigation Canvas
4. Context Inspector
5. Floating Canvas Toolbar

These zones work together to provide an organized and consistent investigation experience.

---

## 4.2 Information Architecture

### 1. Investigation Sidebar

**Purpose:** Provide access to investigation-related information and workspace navigation.

**Main Elements:**
- Investigation list
- Current investigation details
- Entity categories
- Saved groups or collections
- Data sources
- Navigation options

**User Actions:**
- Open an investigation.
- Switch between investigations.
- Browse available entity categories.
- Access saved information and groups.

### 2. Top Navigation Bar

**Purpose:** Provide global controls and access to important workspace actions.

**Main Elements:**
- Synapse logo and application identity
- Current investigation name
- Search option
- Undo and redo controls
- View or workspace settings
- User or account menu

**User Actions:**
- Identify the current investigation.
- Search for relevant information.
- Access global workspace controls.
- Manage general workspace settings.

### 3. Infinite Investigation Canvas

**Purpose:** Serve as the main workspace for visualizing and exploring investigative information.

**Main Elements:**
- Entity nodes
- Semantic relationship connections
- Entity groups and clusters
- Canvas background and grid
- Investigation overview

**User Actions:**
- Add entity nodes.
- Select and move nodes.
- Connect related entities.
- Arrange and group information.
- Pan and zoom across the canvas.
- Explore connected information.

### 4. Context Inspector

**Purpose:** Display additional information about a selected entity or relationship.

**Main Elements:**
- Entity name and identifier
- Entity type
- Description and metadata
- Associated information
- Connected entities
- Relationship details

**User Actions:**
- Inspect selected entities.
- Review available metadata.
- Explore connected entities.
- Examine relationship information.

### 5. Floating Canvas Toolbar

**Purpose:** Provide quick access to frequently used canvas interactions.

**Main Elements:**
- Select tool
- Pan tool
- Add entity option
- Connect or relationship tool
- Group option
- Zoom controls

**User Actions:**
- Select and move canvas elements.
- Navigate the canvas.
- Add entity nodes.
- Create connections.
- Organize related nodes.
- Adjust the canvas zoom level.

---

## 4.3 Entity Information Architecture

Synapse organizes investigative information into different entity types.

Each entity is represented as a node on the investigation canvas.

### Primary Entity Types

| Entity Type | Description | Example |
|---|---|---|
| Person | Represents an individual involved in an investigation. | Individual or contact |
| Organization | Represents a company, institution, or other organization. | Company |
| Transaction | Represents a financial or recorded transaction. | Financial transaction |
| Communication Record | Represents a communication-related record. | Phone record |
| Legal Document | Represents a document relevant to an investigation. | Case-related document |

### Entity Node Structure

Each entity node should provide a consistent information structure.

**Basic Node Information:**
- Entity name or identifier
- Entity type
- Primary identifying information
- Visual entity indicator
- Relationship connection points

Additional information can be displayed through the Context Inspector.

---

## 4.4 Relationship Architecture

Relationships represent connections between different entities within an investigation.

They are displayed as visual links between entity nodes.

### Relationship Components

- **Source Entity:** The entity from which a relationship originates.
- **Target Entity:** The entity connected to the source.
- **Relationship Type:** The category or meaning of the connection.
- **Relationship Label:** A short description of the connection.
- **Relationship Details:** Additional information available for inspection.

### Relationship Examples

| Source Entity | Target Entity | Relationship Example |
|---|---|---|
| Person | Organization | Associated with |
| Person | Person | Connected to |
| Organization | Organization | Business relationship |
| Person | Transaction | Involved in |
| Transaction | Organization | Associated with |
| Person | Legal Document | Mentioned in |

Relationship examples are illustrative. Actual relationship types should depend on the available investigative data and confirmed project requirements.

---

## 4.5 Spatial Workspace Structure

The Synapse workspace is organized to keep the main investigation canvas central while providing supporting tools around it.

### Workspace Layout

**Left Zone — Investigation Sidebar**

Contains investigation navigation, entity categories, and saved groups.

**Top Zone — Navigation Bar**

Contains the application identity, current investigation information, search, and global controls.

**Center Zone — Infinite Investigation Canvas**

Contains entity nodes, relationships, groups, and the main visual investigation workspace.

**Right Zone — Context Inspector**

Displays details about the currently selected entity or relationship.

**Floating Zone — Canvas Toolbar**

Provides quick access to selection, navigation, entity creation, connection, grouping, and zoom actions.

The canvas remains the primary focus of the interface.

---

## 4.6 Semantic Zoom System

Synapse uses three semantic zoom levels to adapt the amount of information displayed according to the user's viewing scale.

### Micro Level — Detailed Exploration

**Purpose:** Focus on individual entities and their information.

**Display Rules:**
- Show detailed entity information.
- Display entity names and identifiers clearly.
- Make relevant metadata accessible.
- Show relationship labels where appropriate.
- Allow users to inspect individual nodes.

**Primary User Activity:** Examining specific entities and their details.

### Macro Level — Relationship Exploration

**Purpose:** Understand connections between multiple entities.

**Display Rules:**
- Show compact entity representations.
- Prioritize important relationship connections.
- Display relevant relationship labels.
- Support visual grouping of related nodes.
- Reduce secondary information that is not essential at this scale.

**Primary User Activity:** Exploring relationships and connected entities.

### Meta Level — Network Overview

**Purpose:** Understand the broader structure of the investigation.

**Display Rules:**
- Represent groups of entities as visual clusters.
- Highlight broader network structures.
- Reduce individual node details.
- Prioritize major connections and patterns.
- Maintain a clear overview of the investigation.

**Primary User Activity:** Reviewing clusters and understanding the overall network.

---

## 4.7 Spatial Interaction Rules

The following rules define how users interact with the investigation canvas.

### Rule 1: Canvas Navigation

Users should be able to move across the investigation workspace using pan interactions.

The canvas should support navigation beyond the initially visible area.

### Rule 2: Zoom Interaction

Users should be able to zoom in and out of the canvas.

The displayed information should adapt according to the active semantic zoom level.

### Rule 3: Node Selection

Selecting an entity node should make its relevant information available in the Context Inspector.

The selected node should have a clear visual state.

### Rule 4: Node Movement

Users should be able to reposition entity nodes within the canvas.

Moving a node should preserve its relationship connections.

### Rule 5: Relationship Visualization

Connections between entities should be visually distinguishable from the entity nodes themselves.

Relationship labels and details should remain accessible when relevant.

### Rule 6: Entity Grouping

Related entities should be capable of being organized into visual groups or clusters.

Grouping should help users understand the investigation without hiding important relationships.

### Rule 7: Context Preservation

Users should be able to inspect an entity while maintaining their position and orientation within the investigation canvas.

### Rule 8: Visual Consistency

Entity nodes, relationship connections, selection states, and zoom behavior should follow consistent visual and interaction patterns.

---

## 4.8 Information Hierarchy

The information hierarchy determines which elements receive priority within the workspace.

| Priority | Element | Purpose |
|---|---|---|
| Primary | Investigation Canvas | Main workspace for visual exploration |
| Primary | Entity Nodes | Represent investigative entities |
| Primary | Relationship Connections | Communicate relationships |
| Secondary | Investigation Sidebar | Workspace navigation |
| Secondary | Context Inspector | Entity and relationship details |
| Secondary | Floating Canvas Toolbar | Canvas interaction controls |
| Supporting | Top Navigation Bar | Global controls and navigation |

The visual hierarchy should keep investigative information at the center of the experience while making supporting tools accessible.

---

## 4.9 Key Design Principles

The information architecture and spatial rules of Synapse are guided by the following principles:

1. **Canvas-Centered Design:** Keep the investigation canvas as the primary workspace.
2. **Clear Information Hierarchy:** Make entities and relationships easy to identify.
3. **Progressive Disclosure:** Show information according to the user's current level of exploration.
4. **Context Preservation:** Allow users to inspect details without losing the broader investigation view.
5. **Consistent Interaction:** Maintain predictable behavior across canvas tools and entity types.
6. **Scalable Organization:** Support increasingly complex networks through grouping and semantic zoom.
7. **Visual Clarity:** Reduce unnecessary visual complexity while preserving meaningful information.

---

## 4.10 Expected Outcome

The information architecture and spatial rules establish the structural foundation for the Synapse interface.

The resulting design should provide:

- A clearly organized five-zone workspace.
- A central infinite investigation canvas.
- Consistent entity and relationship structures.
- A contextual information inspection system.
- Accessible canvas interaction tools.
- Three semantic zoom levels: Micro, Macro, and Meta.
- Clear spatial interaction and navigation rules.

These specifications will guide the wireframing, interface design, and high-fidelity prototyping stages of Synapse.

---

**Scope Note:** This document describes the proposed interface architecture and interaction rules. Specific controls, import methods, data structures, and automated behaviors should be finalized according to the approved project requirements.
