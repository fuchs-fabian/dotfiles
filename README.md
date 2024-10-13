# `dotfiles` - Useful dotfiles for Linux environments

<div align="center">
  <a href="https://github.com/fuchs-fabian/dotfiles">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=fuchs-fabian&repo=dotfiles&theme=holi&hide_border=true&border_radius=10" alt="Repository dotfiles" />
  </a>
</div>

## `.bashrc` and `.zshrc` configuration with `.rcconf`

`.rcconf` is a file that contains aliases and functions for the Linux environment. It is used to configure the `.bashrc` and `.zshrc` files. The aliases and functions are used to simplify the usage of the terminal.

To get a quick overview of which aliases and functions can be used, simply execute the following in the terminal after installation:

```shell
alf
```

### Installation

`.bashrc`:

```shell
wget -O ~/.rcconf https://raw.githubusercontent.com/fuchs-fabian/dotfiles/refs/heads/main/src/.rcconf && \
echo -e '\nsource ~/.rcconf' >> ~/.bashrc && \
source ~/.bashrc && \
echo "'.rcconf' downloaded and updated in '.bashrc'"
```

`.zshrc`:

```shell
wget -O ~/.rcconf https://raw.githubusercontent.com/fuchs-fabian/dotfiles/refs/heads/main/src/.rcconf && \
echo -e '\nsource ~/.rcconf' >> ~/.zshrc && \
source ~/.zshrc && \
echo "'.rcconf' downloaded and updated in '.zshrc'"
```

### Update

`.bashrc`:

```shell
wget -O ~/.rcconf https://raw.githubusercontent.com/fuchs-fabian/dotfiles/refs/heads/main/src/.rcconf && \
source ~/.bashrc && \
echo "'.rcconf' updated in '.bashrc'"
```

`.zshrc`:

```shell
wget -O ~/.rcconf https://raw.githubusercontent.com/fuchs-fabian/dotfiles/refs/heads/main/src/.rcconf && \
source ~/.zshrc && \
echo "'.rcconf' updated in '.zshrc'"
```
