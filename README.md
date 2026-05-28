# Dotfiles

Manual deployment of essential dotfiles.

## Files

- [`.gitconfig`](.gitconfig)
- [`.gitignore_global`](.gitignore_global)
- [`.npmrc`](.npmrc)
- [`Microsoft.PowerShell_profile.ps1`](Microsoft.PowerShell_profile.ps1)
- [`0_catppuccin_mocha.omp.json`](0_catppuccin_mocha.omp.json)

## Usage

Copy or link each file to its target location:

- Git config: `%USERPROFILE%\.gitconfig`
- Git global ignore: `%USERPROFILE%\.gitignore_global`
- NPM config: `%USERPROFILE%\.npmrc`
- PowerShell profile: `%USERPROFILE%\Documents\PowerShell\Microsoft.PowerShell_profile.ps1`
- oh-my-posh theme: `%USERPROFILE%\AppData\Local\Programs\oh-my-posh\themes\0_catppuccin_mocha.omp.json`

On Linux/macOS use `$HOME` paths accordingly.
