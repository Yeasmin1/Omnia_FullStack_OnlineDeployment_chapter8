##Add Deno to PATH: If Deno is installed but the terminal still can't find it, you might need to add Deno to your PATH. You can do this by adding the following line to your shell configuration file (~/.zshrc, ~/.bashrc, or ~/.bash_profile, depending on your shell):
export DENO_INSTALL="$HOME/.deno"
export PATH="$DENO_INSTALL/bin:$PATH"
