# Claude Code Analysis Project

## Project Overview
This project aims to analyze the design and implementation of Claude Code, a popular AI agent tool that runs in terminal environments. Since Claude Code is not currently open source, this analysis uses legal and appropriate reverse engineering approaches.

## Analysis Approaches

### 1. Static Analysis
- Analyze minified and compiled JavaScript code (`cli.js`)
- Design and implement analysis systems and tools
- Extract architectural patterns and implementation details from compiled code

### 2. Dynamic Analysis
- Apply monkey patching techniques to intercept and analyze runtime behavior
- Monitor API request patterns and behaviors
- Analyze system interactions during actual execution

## Project Structure
- `notes/` - Personal analysis notes (gitignored, not for public repository)
- `cli.js` - Original minified Claude Code executable (very large file)
- `yoga.wasm` - WebAssembly module copied from Claude Code
- `CLAUDE.md` - This project documentation
- `AGENTS.md` - Agent-specific analysis and documentation

## Important Notes
- All analysis methods follow legal reverse engineering practices
- The `cli.js` file is extremely large and should not be read in its entirety directly
- Focus on targeted analysis of specific components and behaviors
- Document findings and methodologies for reproducibility