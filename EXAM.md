
# SSH Cloning

ssh-keygen -t ed25519 -C "oscgomgon.business@gmail.com"

eval "$(ssh-agent -s)"

ssh-add ~/.ssh/id_ed25519

cat ~/.ssh/id_ed25519.pub
y copiarla en github ssh keys

git clone git@github...