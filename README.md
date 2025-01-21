# Blockify 🤖

<div align="center">
  <img src="https://pbs.twimg.com/profile_banners/1879192210756820992/1736869471/1500x500" width="100%" />
</div>

## ✨ Features

- 🛠️ Blockify is a node based platform that allows its users to create customized agents and algorithms without the need of code. 
Our app is almost finished, can't wait to share it with you all.
- 🔗 Support for every framework Eliza, Arc, ZerePy, Sora.

## 🎯 Use Cases

- 🤖 Chatbots
- 🕵️ Autonomous Agents
- 📈 Business Process Handling
- 🧠 Trading

### Prerequisites

- [Python 2.7+](https://www.python.org/downloads/)
- [Node.js 23+](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
- [pnpm](https://pnpm.io/installation)

> **Note for Windows Users:** [WSL 2](https://learn.microsoft.com/en-us/windows/wsl/install-manual) is required.

### Use the Starter (Recommended)

```bash
git clone https://github.com/soserer/Blockifynode
cd blockify-starter
cp .env.example .env
pnpm i && pnpm build && pnpm start
```
#### Checkout the latest release

```bash
# Clone the repository
git clone https://github.com/soserer/Blockifynode.git

# This project iterates fast, so we recommend checking out the latest release
git checkout $(git describe --tags --abbrev=0)
# If the above doesn't checkout the latest release, this should work:
# git checkout $(git describe --tags `git rev-list --tags --max-count=1`)
```

#### Edit the .env file

Copy .env.example to .env and fill in the appropriate values.

```
cp .env.example .env
```

Note: .env is optional. If you're planning to run multiple distinct agents, you can pass secrets through the character JSON

#### Start Blockifynode

```bash
pnpm i
pnpm build
pnpm start

# The project iterates fast, sometimes you need to clean the project if you are coming back to the project
pnpm clean
```

### Interact via Browser

Once the agent is running, you should see the message to run "pnpm start:client" at the end.

Open another terminal, move to same directory, run the command below, then follow the URL to chat with your agent.

```bash
pnpm start:client
```

Then read the [Documentation](https://github.com/soserer/Blockifynode) to learn how to customize your Blockify interface.

---

#### Additional Requirements

You may need to install Sharp. If you see an error when starting up, try installing it with the following command:

```
pnpm install --include=optional sharp
```

---

### Community & contact

- [GitHub Issues](https://github.com/soserer/Blockifynode). Best for: bugs you encounter using Blokify, and feature proposals.
- [X](https://x.com/blockifynode). Best for: sharing your applications and hanging out with the community.



