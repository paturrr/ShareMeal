# Rules for Antigravity (AGY)

## Always Use RTK (Rust Token Killer)
To optimize token usage and operations:
1. When running any CLI commands (like `git`, `npm`, `composer`, `php`, etc.), prefer using the `rtk` proxy hook or invoking commands through `rtk` directly when necessary.
2. For meta operations or debugging, use:
   - `rtk gain` to check token savings analytics.
   - `rtk discover` to analyze command history.
   - `rtk proxy <cmd>` to run a raw command bypassing filters if troubleshooting is needed.
3. Trust transparent rewrites for standard commands but ensure they are compatible with RTK.
