

1. 安裝 ibus  鍵盤管理工具

 sudo apt-get install ibus ibus-gtk ibus-gtk3 ibus-qt4

2. 安裝 新酷音輸入法

 sudo apt-get install ibus-chewing

3.轉換成  ibus 鍵盤管理

   im-switch -s ibus

4.設定 ibus 支援的輸入法

   ibus-setup

 

input method -> customize active input methods (勾選)

select an input method -> 選取新酷音後按下右邊的 Add

之後就可以透過按下　ctrl + space 切換輸入法


--------------------how to intstall zsh and its font---------------------------
1. sudo apt-get install zsh //install zsh default
2. sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)" //install oh my zsh
3. git clone https://github.com/bhilburn/powerlevel9k.git ~/.oh-my-zsh/custom/themes/powerlevel9k //install powerlevel9k 
4. vim ~/.zshrc //change the theme
5. find ZSH_THEME="powerlevel9k/powerlevel9k"
6. sudo apt-get install fonts-powerline


--------------------how to shorter zsh cmd--------------------------------
1. cd ~/.oh-my-zsh/custom/powerlevel9k/powerlevel9k/
2. sudo apt-get install vim
3. vim powerlevel9k.zsh-theme 
4. find and fix to <set_default POWERLEVEL9K_CONTEXT_THEMLATE "">


------------------boot menu way-------------------------------------------
>> 桌上型電腦 <<

電腦一開機啟動時，按下鍵盤上的按鍵

Asus(華碩):【F8】鍵

Acer(宏碁):【F12】鍵

DELL(戴爾):【F12】鍵

GigaByte(技嘉):【F12】鍵

HP(惠普):【F9】鍵

IBM(聯想):【F12】鍵

Intel(英特爾):【F10】鍵

MSI(微星):【F11】鍵


>> 筆記型電腦 <<

電腦一開機啟動時，按下鍵盤上的按鍵

Asus(華碩):【Esc】鍵

Acer(宏碁):【F12】鍵

DELL(戴爾):【F12】鍵

GigaByte(技嘉):【F12】鍵

GENUINE(捷元):【F1】鍵

HP(惠普):【F9】鍵

Lenovo(聯想):【F12】鍵

MSI(微星):【F11】鍵

SONY(索尼):【F11】鍵

P>TOSHIBA(東芝):【F12】鍵

若您不知道你的電腦開機選項功能鍵:

您可按其他按鈕【Esc】【F1】【F8】【F9】【F10】【F11】【F12】等試看看!!

