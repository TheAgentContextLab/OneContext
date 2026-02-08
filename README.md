# OneContext
 OneContext is an Agent Self-Managed Context layer, it gives your team a ***unified context for ALL AI Agents***, so anyone, any agent can pick up from the same context.

## Key Features
1. Run your Agents with OneContext and it records your Agents trajectory.
2. Share Agent Context so Anyone can Talk to it on Slack.
3. Load the Context to Agents, so Anyone can Continue from the Same Point.
  
## Quick Install
 Install: 
 ```
 npm i -g onecontext-ai
 ```

 This will automatically install the latest ```onecontext-ai``` Python package using the best available Python package manager (```uv``` > ```pipx``` > ```pip3``` > ```pip```).
 
 **Prerequisites**
 * Node.js >= 16
 * Python 3.8+ with one of: ```uv```, ```pipx```, ```pip3```, or ```pip```

## Quick Start
Run: 
```
onecontext
```

## Usage
After installation, the following commands are available:
```
onecontext-ai <command> [args...]
onecontext <command> [args...]
oc <command> [args...]
```
All three commands are equivalent and proxy to the underlying Python CLI.

**Examples**
```
# Check version
onecontext version

# Show help
onecontext --help

# Short alias
oc version
```

## Updating the Python Package
The npm wrapper installs the latest ```onecontext``` on ```npm``` install.
For normal users, use the unified upgrade command:
```
# Recommended
onecontext update
```

If upgrade routing is broken, repair once and retry:
```
onecontext doctor --fix-upgrade
onecontext update
```
Use ```npm rebuild onecontext-ai``` only when the npm wrapper links/cached paths are stale.

## Troubleshooting
If the commands aren't found after installation:
1. Repair and update: ```onecontext doctor --fix-upgrade && onecontext update```
2. Rebuild wrapper links if needed: ```npm rebuild onecontext-ai```
3. Check that ```onecontext``` is on your PATH: ```which onecontext```


## Issue & Feedback
Feel free to raise an issue ticket for any problems you encounter, or for any features or improvements you’d like to see in the future 🙂

## Update
07-02-2026: First Release
 
