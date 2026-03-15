# dotfiles

## New machine setup

1. Install Homebrew:
   ```sh
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```

2. Clone this repo and install everything:
   ```sh
   git clone https://github.com/elliottregan/dotfiles.git ~/Projects/dotfiles
   cd ~/Projects/dotfiles
   brew bundle
   ```

3. Authenticate:
   ```sh
   gh auth login
   gh auth setup-git
   ```

4. Install Claude Code:
   ```sh
   curl -fsSL https://claude.ai/install.sh | sh
   ```
