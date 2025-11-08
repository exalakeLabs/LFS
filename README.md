## 🔍 Checking Your Git LFS Usage

You can check your current **Git Large File Storage (LFS)** usage directly from the GitHub UI or via the command line.

---

### 🧭 From GitHub Repository Settings

1. Go to your repository on GitHub.  
2. Click **⚙️ Settings → Git LFS**.  
3. The page will display:
   - **Current usage** (how much storage and bandwidth you’ve used)
   - **LFS quota owner** (your account or your organization)
   - **Option to purchase more data packs** (if you’re nearing your limit)

---

### 💻 From the Command Line

You can also inspect your LFS usage and tracked files using Git commands:

```bash
# Fetch all LFS objects for the repository
git lfs fetch --all

# List all files currently tracked by Git LFS
git lfs ls-files
