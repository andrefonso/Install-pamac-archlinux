# Install-pamac-archlinux
## Tutorial para instalação do PAMAC (AUR) no Arch Linux

<img src="/imagens/pamac.png">

1) Instalar o _git_ e o _go_ digitando o comando:</br>
   ``sudo pacman -S git go``

2) Baixar o _Yay_ para utilizar o _AUR_:</br>
   `git clone https://aur.archlinux.org/yay.git`

3) Acessar o diretório _yay_:</br>
 `cd yay`

4) Digitar o seguinte comando para instalar o _yay_:</br>
  `makepkg -si`

5) Executar o comando a seguir para instalar o **Pamac**:</br>
   `yay -S pamac-aur`

6) Instalar o _Flatpak_:</br>
  `sudo pacman -S flatpak`

7) Após a instalação basta digitar **pamac** na barra de procura de pastas e arquivos na interface gráfica para acessar a loja de aplicativos.
