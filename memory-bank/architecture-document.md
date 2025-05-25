## Initial MVP Technology Stack Decision

Based on the project's immediate goals for an initial MVP, market focus, and the need for technical simplification at the outset, the following key technology decision has been made for **"Step 1.1: Finalize Basic Technical Architecture & Sub-Technology Selection"**:

*   **Blockchain Framework for MVP:** **Hyperledger Fabric** will be the chosen blockchain framework for the initial Minimum Viable Product (MVP).
*   **Deployment Infrastructure:** The MVP will be deployed on the **Blockchain-based Service Network (BSN)**.
*   **Initial Market Focus:** The initial MVP development and rollout will be focused on the **Indonesian market**.

### Rationale:

This decision is based on the following factors:
1.  **Local MVP Focus:** Aligning with the implementation plan to potentially focus the MVP on a single country for initial technical simplification. Given the user's location, Indonesia is the logical starting point.
2.  **Hyperledger Fabric Suitability:** As outlined in `tech-stack.md` and the business proposal, Hyperledger Fabric offers enterprise-grade security and is a mature platform well-suited for building a trusted identity solution.
3.  **BSN for Infrastructure:** Utilizing BSN aligns with the project's strategy to reduce infrastructure costs and ensure future cross-border compatibility. BSN's support for various frameworks, including Hyperledger Fabric, makes it an ideal choice.
4.  **Phased Approach for FISCO BCOS:** FISCO BCOS, noted for its performance and compliance with Chinese regulations, will be considered for integration or as a primary focus during later expansion into the Chinese market. This phased approach allows for initial simplification without precluding future multi-framework support, leveraging BSN's interoperability.
5.  **MVP Simplification:** Selecting a single blockchain framework for the MVP streamlines initial development, testing, and iteration, which is crucial for validating core functionalities efficiently.

### Architectural Implications:

This decision will guide the detailed technical architecture for the MVP, focusing on:
*   Specific versioning and configuration of Hyperledger Fabric on BSN.
*   Node deployment strategy within the BSN environment.
*   Design of smart contracts (chaincode) for DID management and initial verifiable credentials (e.g., "business registration") tailored for Hyperledger Fabric.
*   API design for frontend and backend services interacting with the Hyperledger Fabric network on BSN.

The overall architecture will, however, be designed with modularity and flexibility in mind to accommodate the future integration of FISCO BCOS and expansion to other markets, leveraging the interoperable nature of BSN. 