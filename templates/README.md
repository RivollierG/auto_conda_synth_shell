# Use other templates

If you want to save your config (and overwrite the default back up):

```bash
cd ~/auto_conda_synth_shell
cp synth-shell-prompt.config templates/synth-shell-prompt.config.bak
```

If you want to use another config file that might be in this folder:

```bash
cd ~/auto_conda_synth_shell
cp templates/<filename> synth-shell-prompt.config
source ~/.bashrc
```

If you want to revert:

```bash
cd ~/auto_conda_synth_shell
cp templates/synth-shell-prompt.config.bak synth-shell-prompt.config
source ~/.bashrc
```

