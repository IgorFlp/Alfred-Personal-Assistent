# Alfred
Alfred is an open-source plug and play personal assistant / Project manager AI agent for Hermes agent.

# Philosofy
Alfred is part of a bigger open-source local AI project that focus on data ownership and privacy, allowing users to run personal assistant at home with no subscription or sending user data for companies.

DISCLAIMER: Data privacy depends on the model and provider set on hermes setup, you can use FREE models via openrouter and have great results at zero cost, run with a paid api or subscription with some cost but higher privacy (If the provider really are loyal to their statements) or run a local model for absolute FREE and Private assistant.

The goal is to make the agent the most efficient possible, enabling you to run at home with small models on 8GB VRAM GPUs, but on current state i daily drive it with a 120b nvidia super free via openrouter, its enough to handle sequence of actions and changes like meetings for deciding agenda, i tried it with a 30b model (nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free), its enough to handle single prompts and tool calls like "schedule this meeting for tomorrow" but is VERY brittle on longer interactions. also tested with 8b localy ran models, its berely enough to call tools and not usable at all now.


# Key features
## Obsidian.md
Alfred is designed to work on obsidian vaults, especially with the obsidian task plugin, being able to take notes, review tasks, create new tasks and more.

Main options
- Create task: Agent schetches a task and ask for aproval to write on your vaulty 
- Take notes: Agent take what you writen or dictated and save on the vault without the need of opening a tab.
- Review tasks: Agent runs a regex search on the tasks pattern and remind you of every undone tasks you might forgoten.

## Google Agenda:
    - Schedule: Agent schedules a new appointment on your google calendar/agenda.
    - Reschedule: Agent can review and reschedule appointments.

## Clickup MCP:
    - Project manager: Agent can create, move and manage a whole clickup project helping you developing your projects.




# How to use
1. Install hermes agent
2. Configure hermes fully
3. Run "Profile-installer.exe"