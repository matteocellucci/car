# Cellux's Arch Rice

My boiled ArchLinux rice without link or installation script.

## Installation
1. Clone the repository
```
git clone --bare https://github.com/matteocellucci/car.git $HOME/.car
```
2. Add an alias into your shell runcom file
```
alias dots="git --git-dir=$HOME/.car/ --work-tree=$HOME"
```
3. Ignore untrucked files
```
dots config status.showUntrackedFiles no
```

