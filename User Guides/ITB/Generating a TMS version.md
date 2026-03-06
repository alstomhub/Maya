# Guide to ITB Generation for TMS

This guide provides a comprehensive overview of the ITB (Interface of Bus Terminal) generation process within the context of the TMS. We will cover the key components involved in this process, including Technical Topology, Track Plan, Operational Topology, and Network Topology.

---

## Structure of the Guide
### 0. [[#General]]
-  Repository Structure.
- COS.
- Railml.
- Initial Configuration.

### 1. Technical Topology
- Overview of the technical topology for implementing the TMS Level 1.
- Adapter.
- Building.
- Update Manager.
- Stations.
- Lines.
- Border Configuration.
- Gate Stations.
- Interface Track Circuits
- Platforms

### 2. Track Plan
- Berths

### 3. Operational Topology
- Overview of the operational topology for implementing the TMS Level 2.
- Gate Stations.

### 4. Network Topology
- Overview of the operational topology for implementing the TMS Level 2.


---
# General
### Repository Overview


The repository comprises several folders, primarily focused on different versions of a specific application within the TMS (Transportation Management System). The structure is organized as follows:

![[Pasted image 20260306170601.png|137]]

#### 1. Yellow Folders: General Documents and Configurations
- **01_Documents**: Contains essential documentation relevant to the project.
- **02_GenericApplication**: Includes generic configurations applicable across various versions.

#### 2. Green Folders: Regional Versions of the Specific Application
- The repository features individual folders for each region, labeled with specific identifiers (e.g., `03_SpecificApplication_MXTM`, `03_SpecificApplication_MXTM_ILX15_16`, etc.). Each folder corresponds to a distinct version of the application tailored for that region.

At the conclusion of the project, all regional versions will be consolidated into a single folder, representing the complete integration of the application across all regions.





