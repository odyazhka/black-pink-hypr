# black-pink-hypr
## Скриншоты

#### Терминал
<img width="1920" height="1080" alt="изображение" src="https://github.com/user-attachments/assets/a9958fcf-bbf1-4c96-a493-129dbb647bbb" />



#### Пояснение иконок панели
<img width="1920" height="1080" alt="скрин" src="https://github.com/user-attachments/assets/9954a80a-6866-41a9-a91a-8789338119d2" />




#### Меню пуск

1. По нажатии клавиши win
<img width="1920" height="1080" alt="изображение" src="https://github.com/user-attachments/assets/771960a6-370d-49c5-8360-49e50e69e012" />



2.По нажатии кнопки слева
<img width="1920" height="1080" alt="изображение" src="https://github.com/user-attachments/assets/192a9e2a-674c-4886-b711-847e65029003" />



#### Меню выключения по правой кнопке
<img width="1920" height="1080" alt="изображение" src="https://github.com/user-attachments/assets/46ebe727-2250-40d9-a875-91dfc7838064" />



### Меню сети
<img width="1920" height="1080" alt="изображение" src="https://github.com/user-attachments/assets/22e672eb-f1bc-4727-b73f-0ea7469713f2" />



#### Аудиовизуализатор
<img width="1920" height="1080" alt="изображение" src="https://github.com/user-attachments/assets/348a5909-5e28-4c54-9988-502ac6d88dd6" />




#### Панель wlogout
<img width="1920" height="1080" alt="изображение" src="https://github.com/user-attachments/assets/ba85bd89-ea14-4595-856f-d6af87d6d272" />



#### Экран блокировки
<img width="680" height="510" alt="изображение" src="https://github.com/user-attachments/assets/ea92275a-5f77-459f-b4df-47cef7c52768" />

### Некоторые сочетания клавиш:

F6 скриншот области

win+F6 скриншот всего экрана

win+c закрыть окно, win+x свернуть/развернуть, win+z развернуть на весь экран

shift+alt сменить раскладку

ctrl+alt+del панель wlogout


## Установка:

#### 1. Установить необходимые пакеты:
```
sudo pacman -S wofi waybar kitty hyprlock gping blueman cava htop grimblast yay 
yay -S wlogout
```



#### 2. Установить шрифт:

Используется бесплатный шрифт PixelLocale 

Скачать его можно по ссылке:

https://fontstruct.com/fontstructions/show/1765530/pixellocale-v-1-4

Скачайте opentype, распакуйте и переместите в папку */usr/local/share/fonts/*

Обновите кэш командой 

```fc-cache -fv```



#### 3. Добавление конфигов:

Скачайте все папки.

Перенесите папки hypr, cava, waybar, wofi, kitty в *~/.config*



#### 4. Установка wlogout:

Скачанную папку wlogout перенесите в */etc*. Понадобятся рут права, можно перенести сначала в корень *~/* а потом использовать команду:

```sudo mv ~/wlogout /etc/```



#### 5. Курсор и иконки

Курсор я взял отсюда:

https://www.gnome-look.org/p/1914826

Иконки отсда:

https://github.com/vinceliuice/Tela-circle-icon-theme

