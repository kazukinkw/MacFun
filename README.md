# MacFun
Screen Targeting

Modo instalação:
https://github.com/koekeishiya/yabai

Instalação Yabai:

brew install koekeishiya/formulae/yabai

brew services start yabai

sudo yabai --install-sa


Instalação Skhd:

brew install koekeishiya/formulae/skhd
brew services start skhd

### Error ao Executar Fix:
killall Dock
touch ~/.yabairc
chmod +x ~/.yabairc
yabai -m config layout                       bsp
yabai -m config auto_balance                 on
brew services restart yabai
