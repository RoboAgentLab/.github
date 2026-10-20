<div align="center">
  <img src="https://huggingface.co/spaces/RoboAgentLab/README/resolve/main/avatar.png" width="100" alt="RoboAgentLab robot arm and code brackets">
  <h1>RoboAgentLab</h1>
  <p><strong>Agents that Act, Build, and Evolve.</strong></p>
  <p>An open research platform for agentic robotics.</p>
  <p>
    <a href="https://github.com/LV-Robotics-Lab/RoboAgentLab">Platform code</a> ·
    <a href="https://github.com/LV-Robotics-Lab/RoboAgentLab/tree/main/packages/embodied">Documentation</a> ·
    <a href="https://huggingface.co/RoboAgentLab/datasets">Datasets</a>
  </p>
</div>

## Robotics as software engineering

RoboAgentLab brings robot task execution and experimental development into a shared coding-agent workspace. Built on [pi](https://github.com/earendil-works/pi), the platform combines an agent loop and persistent sessions with robotics extensions. Downstream servers provide simulation, robot control, perception, planning, and policy inference; upstream skills explain how to compose these capabilities. The same interfaces are available to agent tool calls and generated Python programs.

## Three complementary roles

| Role | Research focus |
| --- | --- |
| **Act — Agent as Policy** | Select behaviors, orchestrate tools, and write programs that execute robot tasks. |
| **Build — Agent as Infrastructure** | Develop and debug robotics systems, reproduce experiments, and connect data collection, training, and evaluation. |
| **Evolve — Agent as Self-Evolver** | Use feedback to revise and retain reusable components, workflows, and research capabilities. |

## Two streams of research data

- **[Robot policy interactions](https://huggingface.co/datasets/RoboAgentLab/pi-embodied-policy-interactions)** — Agent interactions with robot environments, including observations, decisions, tool calls, and feedback. Our research goal is to distill large-model teachers into compact policy agents that combine task accuracy with fast inference.
- **[Robotics R&D interactions](https://huggingface.co/datasets/RoboAgentLab/pi-embodied-rd-interactions)** — Coding-agent interactions from robotics development, integration, debugging, and testing. Our research goal is to use these traces for domain-specific post-training of open-weight models that can drive the RoboAgentLab harness.

The dataset cards describe the contents and structure of the current releases.

## Research and open resources

Our forthcoming paper, **Agents that Act, Build, and Evolve: A Unified Framework and Platform for Agentic Robotics**, connects these roles within a common framework. We are preparing a coordinated release of the paper, a curated literature list, and RoboAgentLab 1.0.

Explore the [platform repository](https://github.com/LV-Robotics-Lab/RoboAgentLab) and the datasets above to follow the project.
