# automated-archbox

My ansible playbook and other scripts that automate an installation of arch


## Usage

1. Install arch.
2. `ansible-galaxy install -r requirements.yml`
3. `ansible-playbook -K main.yml`

Feel free to apply my dotfiles too (although my gitconfig is there, so you might not want it)

`chezmoi init --apply xiurobert`

## Notes

No neofetch is installed. Install it yourself
