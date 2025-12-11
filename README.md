# AI-102: Azure AI Engineer Associate – Study & Practice Repo

This repository is a companion for preparing for the **Microsoft AI-102: Azure AI Engineer Associate** exam. It is intended as a practical, hands-on workspace where you can explore Azure AI services, build small solutions, and capture notes/labs as you study.

## Repository Structure

- `src/` – Code samples, scripts, and small demos for Azure AI services.
- `docs/` – Study notes, lab instructions, and supporting documentation.
  - `docs/images/` – Diagrams and screenshots used in documentation.

As you build out this repo, keep exam objectives in mind and group content under `src/` and `docs/` accordingly.

## Suggested Usage

1. **Set up your environment**  
 - Install the latest **Azure CLI** and sign in.  
 - Install the **Azure AI Studio** and **Azure Cosmos DB** extensions in VS Code (optional but recommended).  
 - Ensure you have access to an Azure subscription where you can create and clean up AI resources.

2. **Organize by exam domains**  
 For each AI-102 objective, create a short folder/note and at least one practical example:
 - Plan and manage Azure AI solutions.
 - Implement computer vision solutions.
 - Implement natural language processing solutions.
 - Implement knowledge mining / cognitive search.
 - Implement conversational AI / Azure OpenAI–based solutions.
 - Apply Responsible AI and security best practices.

3. **Capture labs and experiments**  
 - Use `docs/` to store **step-by-step labs**, screenshots, and architecture diagrams.  
 - Use `src/` for **repeatable code**: scripts, notebooks, and small services.  
 - Prefer **Azure Cosmos DB** for sample app data where you need scalable, low-latency storage for AI/chat context or user profiles.

4. **Practice deployments**  
 - Try provisioning and wiring up Azure AI services end to end (e.g., Cognitive Search + Azure OpenAI + Cosmos DB).  
 - Document what you created, configuration steps, and cleanup instructions in `docs/`.

## Getting Started Quickly

1. Clone the repo:

```pwsh
git clone https://github.com/Swamy-s-Tech-Skills-Academy-2026/AzAI-102EngineerAssociate.git
cd AzAI-102EngineerAssociate
```

2. Open in VS Code:

```pwsh
code .
```

3. Start by adding a first lab under `docs/` and a small script or notebook under `src/` that exercises one Azure AI service you want to learn.

## Conventions

- Keep examples **small and focused** on a single concept.  
- Prefer **Bicep/ARM or scripts** to create resources so they are easy to tear down.  
- Add short **READMEs inside subfolders** if a sample needs special setup or credentials.

---

Feel free to adapt this structure as your study plan evolves. The goal is to make this repo your single place for AI-102 preparation: notes, labs, and working code.
