# Install-pamac-archlinux
## Tutorial para instalação do PAMAC (AUR) no Arch Linux

<img src="/imagens/pamac.png">

1) Instalar o git e o go digitando o comando:</br>
   ``sudo pacman -S git go``

2) Baixar o Yay para utilizar o AUR:</br>
   `git clone https://aur.archlinux.org/yay.git`

3) Acessar o diretório yay:</br>
 `cd yay`

4) Digitar o seguinte comando para instalar o yay:</br>
  `makepkg -si`

5) Executar o comando a seguir para instalar o **Pamac**:</br>
   `yay -S pamac-aur`

6) Instalar o Flatpak:</br>
  `sudo pacman -S flatpak`

7) Após a instalação basta digitar **pamac** na barra de localização na interface gráfica para acessar a loja de aplicativos.
