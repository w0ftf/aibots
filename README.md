# AIBot Command Help
These commands are available on `AIBot`:
- `.dbask <question>` | Search all bot conversation history and return an AI-synthesized answer. |
- `.dbsearch <terms>` | Raw keyword search — shows up to 5 matching rows directly with no AI synthesis. Useful for quickly checking what's in the database. |
- `.dbstats` | Shows total conversation row counts grouped by bot. | 

These commands are available on the following bots:
 `chatgpt`, `claude`, `deepseek`, `gemma`, `Hugging`, `phi`, `python`

- `.pbreview <url> [password]` | Fetch code from PrivateBin, review it, and start an editing session |
- `.pbapply <instructions>` | Apply requested changes to the active PrivateBin session and upload the revised code |
- `.prompt <text>` | Replace the runtime system prompt |
- `.prompt show` | Show the current runtime prompt |
- `.prompt clear` | Reset the runtime prompt |
- `.aioff` | Disable AI auto-responses in the channel |
- `.aion` | Re-enable AI auto-responses in the channel |