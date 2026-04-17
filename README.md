# ClaudeCode Installation

# 1. Update Termux and Install Dependencies
**Update your system packages and install Node.js and Git.**

 ```
pkg update && pkg upgrade -y
pkg install nodejs-lts git -y
```
# 2. Install Claude Code CLI

```
npm install -g @anthropic-ai/claude-code
```
# Replace Api Key:
```
YOUR_OPENROUTER_API_KEY
```
with your API key:
Get free api key - [https://openrouter.ai/]

# 3. Configure OpenRouter API
```
cat <<EOF >> ~/.bashrc

# Claude Code + OpenRouter Config
export ANTHROPIC_BASE_URL="https://openrouter.ai/api"
export ANTHROPIC_AUTH_TOKEN="YOUR_API_KEY_HERE"
export ANTHROPIC_API_KEY=""
export ANTHROPIC_MODEL="openrouter/free"
EOF

source ~/.bashrc
```
# Starting Claude Code

```
claude
```
# Example 


