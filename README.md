# Space Experiment Visualization Tool

A scalable visualization tool for biological experiments conducted in space, built for the **2024 NASA Space Apps Challenge**.  
This project focuses on datasets **OSD-379** and **OSD-665**, enabling scientists to ingest metadata, generate interactive visualizations, and contextualize experiments in a user-friendly way.

---

## 🌍 Recognition: Global Finalist

We are proud to share that our project was selected as a **Global Finalist** in the **2024 NASA Space Apps Challenge** — one of the top projects worldwide among thousands of teams.

🔗 Check out our official project page: [Space Meatballs – Global Finalist Details](https://www.spaceappschallenge.org/nasa-space-apps-2024/find-a-team/space-meatballs/?tab=details)

---

## Table of Contents

1. [Project Overview](#project-overview)
2. [Objectives](#objectives)
3. [Project Timeline Breakdown](#project-timeline-breakdown)
4. [Team Members](#team-members)
5. [Potential Considerations](#potential-considerations)
6. [UML Diagrams](#uml-diagrams)
7. [Power BI Visuals](#power-bi-visuals)
8. [Conclusion](#conclusion)
9. [To-Do List](#to-do-list)

---

## Project Overview

**Project Name:** Space Experiment Visualization Tool  
**Description:** Develop a scalable tool that generates informative visualizations for biological experiments conducted in space, focusing on **OSD-379** and **OSD-665**. The tool will enable scientists to easily understand and contextualize these experiments.  
**Timeline:** 2 weeks

---

## Objectives

1. Create a tool that programmatically ingests metadata and data from OSD-379 and OSD-665.
2. Generate compelling visualizations that effectively communicate the structure and results of these experiments.
3. Ensure the tool can scale to include other datasets within the NASA Open Science Data Repository (OSDR).
4. Incorporate interactivity to enhance user engagement.

---

## Project Timeline Breakdown

_Certain tasks may vary in duration depending on complexity; this serves as a high-level roadmap._

### Week 1: Tool Development and Data Ingestion

- **Day 1-2 (9/23/24 – 9/25/24): Requirements Gathering**

  - Analyze metadata and datasets for OSD-379 and OSD-665.
  - Define key visual elements (e.g., number of subjects, treatment groups, event timelines).

- **Day 3-4 (9/25/24 – 9/26/24): Tool Architecture Design**

  - Design the architecture for data ingestion.
  - Select visualization libraries/tools (e.g., D3.js, Plotly, Dash).
  - Outline the user interface and interaction flow.

- **Day 5-7: Implement Data Ingestion**
  - Develop scripts to programmatically ingest metadata and data.
  - Clean and structure data for visualization.

### Week 2: Visualization and Interactivity

- **Day 8-9: Initial Visualizations**

  - Build visualizations for experiment design and results.
  - Implement event timelines before/after experiments.

- **Day 10: Add Contextual Information**

  - Connect results to related experiments in OSDR.
  - Include details on treatments and subject groups.

- **Day 11: Interactivity Features**

  - Implement filters, tooltips, and dynamic exploration of datasets.

- **Day 12: Testing & Feedback**

  - Verify visualization accuracy and usability.
  - Gather feedback from scientists with limited space biology experience.

- **Day 13: Finalization**

  - Refine based on feedback.
  - Write documentation and tutorials.

- **Day 14: Presentation & Review**
  - Prepare demo and presentation.
  - Conduct final stakeholder review.

---

## Team Members

- [Harlan](https://gitlab.com/space-meatballs/visualization-tool-for-spaceborne-biological-experiments/-/issues?assignee_id=22861925)
- [Andre](https://gitlab.com/space-meatballs/visualization-tool-for-spaceborne-biological-experiments/-/issues?assignee_id=23069005)
- [Johnpaul](https://gitlab.com/space-meatballs/visualization-tool-for-spaceborne-biological-experiments/-/issues?assignee_id=23054767)
- [Carol](https://gitlab.com/space-meatballs/visualization-tool-for-spaceborne-biological-experiments/-/issues?assignee_id=23069252)
- [Matthew](https://gitlab.com/space-meatballs/visualization-tool-for-spaceborne-biological-experiments/-/issues?assignee_id=23069285)
- [Kaan](https://gitlab.com/space-meatballs/visualization-tool-for-spaceborne-biological-experiments/-/issues?assignee_id=22856063)
- [Everest](https://gitlab.com/space-meatballs/visualization-tool-for-spaceborne-biological-experiments/-/issues?assignee_id=)

---

## Potential Considerations

- **Scalability:** Ensure the tool can adapt to future OSDR datasets.
- **User Experience:** Design for intuitive use, even for scientists with minimal background in space biology.
- **Documentation:** Provide clear guides, tutorials, and inline instructions.
- **Collaboration:** Explore opportunities with space biology/data visualization experts.

---

## UML Diagrams

_Insert UML diagrams here or link to external diagrams._

---

## Power BI Visuals

A preliminary Power BI dashboard was created manually for reference using the CSV data. While full integration may not be planned, the Power BI file can be shared to explore how data compares across groups.  
(Refer to the Word doc for visuals.)

---

## Conclusion

This plan outlines the steps required to build a tool that enhances scientific understanding of spaceborne biological experiments. By focusing on visualization, interactivity, and scalability, the project aims to make space science data more accessible and actionable.

_Each node represents a group, filtered by additional nodes for subgroups._  
_Linked list represented in tree format._  
_Parameter values are consistent across experiments; factor values represent variables._

---

## To-Do List

- [ ] Style the experiment page
- [ ] Query an LLM API to generate images and insert them into the diagram
- [ ] Display metrics table (samples and assays) when the "Result" button is clicked
- [ ] Add a quick stylistic overview of the experiment on the left side of the dashboard
- [ ] Build a chatbot with access to the study data for user Q&A
