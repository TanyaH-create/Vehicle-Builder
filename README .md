# Vehical Builder
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)] 

## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Walkthrough](#walkthrough)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)
- [License](#license)

## Description
The Vehicle Builder is a command-line application designed to allow the user to log information about a car, truck or motorbike and then perform certain actions on the vehicle the user has logged. 


## Installation

1. Clone the repository

2. Navigate to the project directory 
   ```bash
   cd ../Vehicle Builder

3. Requires Node.js to be installed

4. Requires a terminal environment with an editor installed

5. Install 'inquirer' package
   ```bash
   npm install inquirer

6.  Run the application
    ```bash
    node index.js

## Usage
1. Run the application in the terminal:
   ```bash
   node index.js 

2. Select whether you would like to create a new vehicle or perform action on an existing vehicle from the first menu.  

    ![First-Image-Initial-Menu](https://github.com/user-attachments/assets/ef24a2b3-abab-42b2-9723-2fbbd5798cd6)


    There is a pre-existing truck, car and motorbike you can choose from in the existing database:  

    ![Image2-Existing Vehicle](https://github.com/user-attachments/assets/f75f9151-ef32-4fe1-9625-9e07773fb400) 

    If you choose to create a new vehicle you will be given the choice to create a new car, truck or motorbike:

    ![SelectNewVehicle](https://github.com/user-attachments/assets/ce6f7f9c-593a-4e81-ade9-4c3f15efe361)


   You will be prompted for information on the new vehicle you are creating:
   
   ![Motorbike](https://github.com/user-attachments/assets/de81d747-568f-4707-b22f-1fd8e195967e)


4. Once you have created a new vehicle or selected an exising vehicle, you are given a menu of actions to choose from that you can perform on the vehicle. You can perform additional actions until you select exit. You will see feedback from the action you have chosen in the command line.

      Actions include:
      - Starting and stopping the vehicle.
      - Accelerating and decelerating in 5 mph increments.
      - Turning right, left and reversing
      - Motorbikes can perform a wheelie.
      - Trucks can tow other vehicles.
      - Creating a report of the current state the vehicle is in.


      ![Img3-Choices](https://github.com/user-attachments/assets/472d8175-faa6-4ccc-ae6c-c54841dff2fb)


   Feedback on the choice you made will show on the command line. You can also create a report of the vehicle whic will show it's current state:
        
      ![print details](https://github.com/user-attachments/assets/9011a624-4c69-4562-913a-fac0edf65b14)

## Walkthrough

[Walkthrough Video]


## Contributing
Contributions are welcome! Please follow these steps:
1.	Fork the repository.
2.	Create a new branch for your feature or bug fix:
    ```bash
    git checkout -b feature-name
3.	Commit your changes:
    ```bash
    git commit -m "Add feature-name"
4.	Push your branch:
    ```bash
    git push origin feature-name
5.	Submit a pull request.

## Tests
To test the application:
1.	Ensure all dependencies are installed.
2.	Run the application and verify the output:
    ```bash
    node index.js

## Questions

 If you have any questions, feel free to contact me at dougtanyah@gmail.com.

 You can also find me on GitHub at [TanyaH-create](https://github.com/TanyaH-create).



## License
This project is licensed under the MIT license. A complete version of the MIT license is available at [MIT](https://opensource.org/licenses/MIT).
Any contribution made to this project will be icense under the MIT.
 
