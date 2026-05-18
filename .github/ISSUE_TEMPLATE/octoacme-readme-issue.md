name: "Create README for OctoAcme Project Management Docs"
description: "Request to create a comprehensive README that serves as the entry point for all project management documentation with process summary and links."
title: "[Process Doc Update]: Create README for OctoAcme Project Management Docs with process summary and links"
labels: ["documentation", "process improvement"]
body:
  - type: dropdown
    id: process_doc
    attributes:
      label: "Which process document do you want to update?"
      description: "Select the program management process document you want to add content to. This issue is for creating a new README.md in the docs/ folder."
      options:
        - "<new document>"
    validations:
      required: true

  - type: textarea
    id: content_summary
    attributes:
      label: "Summary of New Content"
      description: "Create a comprehensive README for the OctoAcme Project Management Docs"
      value: |
        Create a comprehensive README for the OctoAcme Project Management Docs that:
        - Serves as the entry point for all project management documentation
        - Provides a brief summary of OctoAcme's project management methodology and principles
        - Contains organized links to all existing process documentation files
        - Helps team members quickly navigate and understand the complete project management framework
    validations:
      required: true

  - type: textarea
    id: rationale
    attributes:
      label: "Why is this update needed?"
      description: "Explain the reason for this addition"
      value: |
        The OctoAcme project management documentation is currently scattered across multiple markdown files without a clear entry point or navigation guide. A centralized README would:
        - Improve discoverability of all project management processes
        - Provide new team members with a quick orientation to the methodology
        - Serve as a table of contents for the documentation structure
        - Help stakeholders understand the complete project lifecycle and governance model
    validations:
      required: true

  - type: textarea
    id: example_content
    attributes:
      label: "Suggested Content"
      description: "Proposed README structure with overview, core principles, lifecycle, and documentation links"
      value: |
        # OctoAcme Project Management Documentation

        ## Overview
        OctoAcme uses a structured, customer-first project management approach focused on iterative delivery, clear ownership, data-informed decisions, and psychological safety. This documentation contains guidance for all phases of the project lifecycle.

        ## Core Principles
        - **Customer-first**: Prioritize customer value and usability
        - **Iterative delivery**: Deliver small, testable increments
        - **Clear ownership**: Each project has named roles and responsibilities
        - **Data-informed decisions**: Measure impact and iterate based on evidence
        - **Psychological safety**: Encourage feedback and learning

        ## Project Lifecycle
        1. **Initiation** - Validate business need, align stakeholders, define success criteria
        2. **Planning** - Break work into shippable increments, identify dependencies and risks
        3. **Execution** - Build, test, review, and iterate with regular tracking
        4. **Release** - Deploy to production and verify success
        5. **Retrospective** - Capture learnings and drive continuous improvement

        ## Documentation Links
        - [Project Management Overview](./octoacme-project-management-overview.md)
        - [Project Initiation Guide](./octoacme-project-initiation.md)
        - [Project Planning](./octoacme-project-planning.md)
        - [Execution & Tracking](./octoacme-execution-and-tracking.md)
        - [Risk Management & Communication](./octoacme-risks-and-communication.md)
        - [Release & Deployment Guide](./octoacme-release-and-deployment.md)
        - [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
        - [Roles & Personas](./octoacme-roles-and-personas.md)

  - type: checkboxes
    id: acceptance_criteria
    attributes:
      label: "Acceptance Criteria"
      description: "Check all that apply:"
      options:
        - label: "Content aligns with existing process docs"
          required: true
        - label: "Update improves clarity or closes a documented gap"
          required: true
        - label: "Proposed content has been reviewed with stakeholders (if needed)"
          required: false
