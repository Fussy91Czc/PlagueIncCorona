# PlagueIncCorona

Tutorial - Mine for blocks with Microsoft Windows
Mine for blocks with your Windows wallet and the following instructions.

Click here to download the file plagueinccorona-qt-windows.zip.

Open File Explorer and go to your downloads directory.

Extract the zip file plagueinccorona-qt-windows.zip

Open "Run" with the keyboard shortcut winkey + r.

Enter the following text behind "Open": notepad

Press on the button "OK".

Paste the following into notepad.

addnode=node1.walletbuilders.com

Click on the menu item "File" -> "Save As...".

The open dialog box will appear, click on "Save as type" and select the option "All Files (*.*)".

Enter the following text behind "File name": plagueinccorona.conf

Click on the menu bar, type the following text %appdata% and press on the enter key. enter

Create the folder PlagueIncCorona and open the folder.

Press on the button "Save".

Open your wallet.

Go to Tools -> Debug console.
This is the console where you execute RPC commands.

Type the following command, to mine your first block:

setgenerate true -1

-------------------------------------------------------------------------------------------------------------

Tutorial - Stake for coins with Microsoft Windows
Stake for coins with your Windows wallet and the following instructions.

Click here to download the file plagueinccorona-qt-windows.zip.

Open File Explorer and go to your Downloads directory.

Extract the zip file plagueinccorona-qt-windows.zip

Open your wallet.

Optional: Unlock your wallet for staking.

Go to Settings -> Unlock Wallet.

Tick the option named "For anonymization and staking only".

Enter the your passphrase behind the text "Enter passphrase".

Click on the button "OK".

Stake can only be generated when you have coins in your wallet.

-------------------------------------------------------------------------------------------------------------

Tutorial - Mine for blocks with macOS
Mine for blocks with your macOS wallet and the following instructions.

Open Spotlight Search and type the following:

terminal

Click on terminal.

Execute the following command, to open your downloads directory:

cd Downloads

Install Homebrew with the following command:

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

Enter your sudo password to install Homebrew.

Install wget with the following command:

brew install wget

Download your macOS wallet  plagueinccorona-qt.dmg 

Create the data directory for your coin with the following command:

mkdir "$HOME/Library/Application Support/PlagueIncCorona/"

Open nano.

nano "$HOME/Library/Application Support/PlagueIncCorona/plagueinccorona.conf" -t

Paste the following into nano.

rpcuser=rpc_plagueinccorona
rpcpassword=dR2oBQ3K1zYMZQtJFZeAerhWxaJ5Lqeq9J2
rpcallowip=127.0.0.1
listen=1
server=1
addnode=node1.walletbuilders.com

Save the file with the keyboard shortcut ctrl + x.

Open your downloads directory in Finder.

Install your macOS wallet with the file plagueinccorona-qt.dmg.

Open your wallet.

Go to Tools -> Debug console
This is the console where you execute RPC commands.

Type the following command, to mine your first block:

setgenerate true -1

