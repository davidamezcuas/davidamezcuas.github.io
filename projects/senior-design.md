---
layout: default
title: Senior Design - Agentic AI Circuit Design
---

# Agentic AI System for Circuit Card Design

**Senior Design Project | Iowa State University**

**August 2026 – May 2027 (Expected)**

**Project Status:** In Development

## Project Overview

For my Senior Design project at Iowa State University, I am working alongside a team of Computer Engineering students to develop an artificial intelligence (AI) system that can assist engineers during the early stages of circuit card design.

Designing a circuit board involves much more than simply connecting electrical components. Engineers must research available components, review technical documentation, compare possible design solutions, and establish requirements before beginning the actual design. These processes can be time-consuming, especially when working with large amounts of technical information.

Our project aims to simplify this process by developing a system that uses multiple AI agents, each responsible for a specific engineering task. These agents will work together to retrieve technical information, analyze circuit designs, and generate useful engineering documentation.

The overall goal is not to replace engineers, but to provide tools that can make the design process more efficient, organized, and consistent.

## My Contributions

My primary responsibility involves developing the knowledge management and information retrieval capabilities that support the AI agents.

One of my first tasks was setting up **PathRAG**, a retrieval system that helps AI models locate and connect relevant information from technical documents. I configured PathRAG within a Linux-based Docker environment, installed its required dependencies, and began experimenting with locally hosted language models.

I also worked on setting up **Neo4j**, a graph database that can represent relationships between pieces of information. This technology is being explored as part of our approach to organizing and retrieving engineering knowledge.

Another major part of my work has involved **Obsidian**, which we are using to maintain project-specific information. I created a structured vault containing separate sections for a Bill of Materials (BOM), required components, and components that should be avoided.

To make this information accessible to our AI agents, I developed a Python-based command-line interface (CLI) that supports adding, modifying, removing, and searching component information within the vault.

More recently, I have been exploring how these tools can work together to support a Requirements Agent. This agent is intended to analyze information from circuit schematics and generate structured engineering requirements, such as functional requirements and input/output specifications.

## Skills and Knowledge Acquired

Working on this project has allowed me to expand my understanding of several technologies beyond what I have encountered in traditional coursework.

**Linux and Docker:** I have gained additional experience working in remote Linux environments, configuring development containers, managing dependencies, and troubleshooting software installations.

**Artificial Intelligence and Large Language Models:** I have learned more about locally hosted language models, retrieval-augmented generation, and how AI systems can use external information to support their responses.

**Knowledge Management and Databases:** Through PathRAG, Neo4j, and Obsidian, I have explored different methods of storing, organizing, and retrieving technical information.

**Python and Command-Line Tools:** Developing
