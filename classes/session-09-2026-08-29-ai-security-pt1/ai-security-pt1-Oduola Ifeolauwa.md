# My Notes — ODUOLA Ifeoluwa


## Key Concepts I Learned

<!-- Write the main ideas covered in today's session -->

- Conditional Access policies can be applied to AI agents, not just users, to govern their access based on signals like context, device, and risk.
- Defender for Cloud Apps and Defender XDR are essential for discovering AI agents, assessing their blast radius, analyzing attack paths, and enabling real-time protection.
- AI agents can operate in two main patterns: delegated (acting on behalf of a user) and autonomous (acting on their own credentials), requiring different security configurations.
- Least privilege, attribute-based access control, and regular review/retirement of agent permissions are vital for managing agent lifecycles and minimizing risk.


---

## Lab / Hands-On Work

<!-- Describe what you did in the lab. Include steps, commands, or screenshots descriptions -->

### What I did
-  The presenter demonstrated navigating Microsoft Entra ID to view agent identities, blueprints, and activities. They attempted to create an agent blueprint and identity. The presenter also showed how to access conditional access policies and discussed the process of assigning agents to these policies, noting the requirement for specific licenses . Additionally, they showed how to enable security for AI agents in Defender for Cloud Apps and discussed verifying real-time protection through the agent inventory, alerts, and advanced hunting in Defender XDR

### What happened / Result
- An agent identity was successfully created after obtaining a trial license for Microsoft 365 Agent 3.
- The presenter was able to access and configure conditional access settings for agents, demonstrating how to select agent identities as targets, contingent on the correct licensing .
- Real-time protection features for Copilot Studio agents were enabled in Microsoft Defender for Cloud Apps, with the presenter noting that it requires time to provision and might not immediately show results without further configuration or production data ].


### Challenges I faced

- Licensing limitations were a significant challenge, preventing the full demonstration of features like conditional access for agents and complete visibility in the Defender portal's AI inventory. The presenter had to acquire trial licenses during the session.
- Some features, like agent identity and blueprints, were noted as being in preview, indicating ongoing development and potential instability.
---

## My Takeaways

<!-- What was most valuable to you personally from this session? -->


- The AI agents are not just chatbots; they can perform autonomous tasks, invoke tools, and access resources, making their security as critical as user security. The concept of applying conditional access directly to agent identities, not just users, is a powerful realization for securing these autonomous entities. I also found the explanation of "blast radius" and how to assess it through permissions, knowledge sources, and blueprint configurations to be particularly insightful for proactive risk management.

## Questions I Still Have

<!-- Anything you want to follow up on or ask the mentor -->

- How can organizations effectively manage the lifecycle of AI agents, especially in large-scale deployments, beyond manual reviews? Are there more automated solutions in development or available?
-

---

## Resources I Found Useful

<!-- Any links, docs, or Microsoft Learn modules you found helpful -->

-

---

*Submitted by: Oduola · ife005 *
