# Notebook in GitHub Codespaces (Template)

This repo is a simple starting point to run a Jupyter notebook in **GitHub Codespaces** (browser-only, no installs).

## Quick start
1. Create a **new GitHub repository** and upload these files.
2. On the repo page, click the green **Code** button → **Create codespace on main**.
3. When the Codespace opens, click `notebook.ipynb`.
4. If prompted, select the **Python** kernel and **Trust** the notebook.
5. Run cells. If packages are missing, they are installed automatically. If needed, open the Terminal and run:
   ```bash
   pip install -r requirements.txt
   ```

## Add your own notebook
- Replace `notebook.ipynb` with your own `.ipynb` or add more notebooks.
- Add packages you need to `requirements.txt` (one per line).

## Notes
- The `.devcontainer` config auto-installs packages from `requirements.txt` when the Codespace starts.
- Remember to **commit** any changes in the Codespace to save them back to the repo.
