# Chess Wallet

<p align="center"><img src="pictures/Banner.PNG"></img><br><a href="https://opensource.org/licenses/MIT" title="License: MIT"><img src="https://img.shields.io/badge/License-MIT-blue.svg"></img></a></p>
A brain wallet that is rememberable.

Instead of remembering 24 words in a right order you have instead to remember the setup of a chessboard.
This setup will be the entropy to your 24 words/ to your bitcoins.

## Quality of entropy
A chessboard has 8 by 8 squares. Which equals 64 squares in totall.
There are 13 diffrent states(pieces being on them) one square can be in, including empty.
So there are 64^13 possible combinations.

This [entropy guide](Libraries/EntropyGuide.md) instructs you on what to input. <br>However the Chess-Wallet can be used to input any entropy.

## Disclaimer!
<details>
<summary>see more</summary>

- This was only designed for Bitcoin. No other shitcoin.<br>
- I take no responsibility of my code. If you lose your Bitcoins its your fault.<br>
- You can review the code yourself before using it.<br>
</details>

## Requirements
<details>
<summary>see more</summary>

1. Install the latest version of Python3 [here](https://python.org/downloads/).
    - Check add to PATH in the installation
2. [Download](https://github.com/RealCocoArdo/Chess-Wallet/archive/refs/heads/main.zip) this repository and unzip it. Or clone it.

</details>

## Start the program
<details>
<summary>see more</summary>

1. Navigate to the Chess-Wallet folder and open it
2. Open in the folder Libraries the `install-libraries-windows` or bash the `install-libraries-linux` file to dowload the libraries. You only need to do this once.
3. Disconnect your Wifi
4. Open the `start-on-windows` or bash the `start-on-linux` file to start the program.
</details>
