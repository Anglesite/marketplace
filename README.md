# Anglesite Marketplace

Claude Code plugin marketplace for [Anglesite](https://github.com/Anglesite/anglesite).

## Install

### Claude Cowork

1. Open [Claude](https://claude.ai) and start a Cowork session
2. Open the **Code** tab
3. Press **+** > **Plugins** > **Add Plugin**
4. Select the **Personal** tab, press **+**
5. Select **Add Marketplace from GitHub**
6. Enter `Anglesite/marketplace` and press **Sync**
7. Enable the **anglesite** plugin
8. Create a new folder for your site and open it in the **Code** tab
9. Type `/anglesite:start`

### Claude Code

```sh
claude plugin marketplace add Anglesite/marketplace
claude plugin install anglesite
```

Then start a new project:

```sh
mkdir my-site && cd my-site
claude
```

Type `/anglesite:start` to begin.
