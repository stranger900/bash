# .ps1_prompt file for easier working in ITerm on Mac OS

Add this file to your home directory and include it in your shell's initialization script.

Example: ~/.bashrc (or ~/.bash_profile)
if [ -f "$HOME/.ps1_prompt" ]; then
  source "$HOME/.ps1_prompt"
fi

#### Warning: I've only tested this on MacOS using bash!
