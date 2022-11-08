FROM archlinux

RUN adduser -D nonroot

RUN yes | pacman -Syu
RUN yes | pacman -Syy neovim fuse nodejs python3 python-pip git curl neofetch

# RUN echo y | LANG=C yay --noprovides --answerdiff None --answerclean None --mflags "--noconfirm" asdf-vm
