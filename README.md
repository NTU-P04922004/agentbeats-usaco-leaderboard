# Agentbeats USACO benchmark Leaderboard

## Modify `scenario.toml` as follows:

- **Create participant sections**: Add a `[[participants]]` section for each role your green agent expects
  - Set the name field for each role (e.g., "attacker", "defender")
  - Leave `agentbeats_id` and `env` fields empty for submitters to complete

- **Set assessment parameters**: Add your assessment parameters under the `[config]` section
  - These values get sent to your green agent at the start of each assessment
  - Set default values for your assessments (submitters may customize these)

## Document your leaderboard
Update your README with details about your green agent. Use the debate leaderboard's [README](https://github.com/RDI-Foundation/debate-leaderboard) as a reference for structure and content.

Include:
- Brief description of your green agent and what it orchestrates
- How scoring/evaluation works
- Any configurable parameters (like task specification)
- Requirements for participant agents
