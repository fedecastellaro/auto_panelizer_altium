# Altium PCB Panel Generator Script

This repository contains a DelphiScript for Altium Designer that automates the generation of a panel based on an existing PCB design. This script simplifies the process of creating panels for PCB fabrication, making it more efficient and error-free.

    ![Alt text](images/gui.png?raw=true)

## Introduction

When designing PCBs in Altium Designer, creating panels for fabrication is a common and crucial step. Manually creating these panels can be time-consuming and error-prone. This DelphiScript automates the panel creation process, saving you time and reducing the risk of mistakes.

## Features

* **Automated Panel Generation:** The script takes an existing PCB design and generates a panel layout based on user-defined parameters.
* **User-Friendly:** The script provides a user-friendly interface within Altium Designer, making it accessible to both novice and experienced users.
* **Customizable:** You can customize the script to suit your specific panelization requirements.

## Usage

1. Clone or download this repository to your local machine.
2. Open Altium Designer.
3. Create a new PCB document where you want the panel to be generated .
4. In Altium Designer, go to `File` -> `Run Script...`.
5. Browse and select the **Panelizer.PrjScr** file from the downloaded repository.
6. Select the desired PCB to panelize with the Search button.
7. Select the number of boards in X and Y.
8. Select the column and row spacing desired.
9. Set the position of the embedded PCB boards.
10. Click OK et voilà.

## Contributing

Contributions to this project are welcome. If you have any ideas for improvements or new features, feel free to fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the [MIT License](https://chat.openai.com/c/LICENSE). You are free to use, modify, and distribute this script as per the terms of the license.