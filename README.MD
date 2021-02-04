Clone repo into new hidden directory.
# Use SSH (if set up)...
git clone git@github.com:DacianCoder/.dotfiles.git ~/.dotfiles

# ...or use HTTPS and switch remotes later.
git clone https://github.com/DacianCoder/.dotfiles.git ~/.dotfiles
Create symlinks in the Home directory to the real files in the repo.
# There are better and less manual ways to do this;
# investigate install scripts and bootstrapping tools.

ln -s ~/.dotfiles/.zshrc ~/.zshrc
ln -s ~/.dotfiles/.gitconfig ~/.gitconfig