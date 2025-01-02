# Vehicle Manipulator

  ## License
  [![License: CC0-1.0](https://licensebuttons.net/l/zero/1.0/80x15.png)](http://creativecommons.org/publicdomain/zero/1.0/)
  [Creative Commons licenses (for documentation)](http://creativecommons.org/publicdomain/zero/1.0/)

  ## Contents
  ---------
  - [License](#license)
  - [Description](#description)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Contribution](#contribution)
  - [Tests](#tests)
  - [Questions](#questions)

  ## Description
  This program will allow you to either create a new vehicle and manipulate it from a set of listed actions or choose from a selection of already created vehicles to manipulate.  In addition any vehicles created wiill then be added to the list of previously generated vehicles and be usable from then on.

  ## Installation
  First you will need to clone the repo to your own local storage. 
  
  git clone git@github.com:bjaegerthomas/Vehicle-Manipulator.git
  
  Then you will navigate to the "dist" folder inside the localalized repo you just created.

  Once inside the dist folder you will simply type from the terminal line:

  node index.js

  Then hit enter to initialize the program.

  ## Usage
  After you have initialized the program you will be prompted to either create a new vehicle or perform an action on an existing vehicle:

  ![Starting prompt](./assets/start.png)

  Let's begin by choosing a pre-existing vehicle. Using the arrow keys, navigate to your selection and press enter.
  You will then be presented with the choice of three pre-generated vehicles. One truck, one car, and one motorbike.

  ![Vehicle Selection](./assets/select.png)

  For now we will select the car by navigating using the arrow keys and hitting enter after our selection is highlighted.
  Once we have chosen our vehicle we will be presented with a series of actions we can perform with it.

  ![Actions available](./assets/actions.png)

  You will need to start the vehicle before you are able to perform other actions on it like accelerating or decelerating. You may continue to manipulate the vehicle as much as you want via the commands listed. When you are finished with the current vehicle you can choose the option "select or create another vehicle" to continue using the program with a different vehicle.

  When you have finsihed with the program completely, simply choose the "exit" option from the list of proposed actions.

  ----------------------------------------------------------------------------------------------------------------------

  The actions available for manipulating the vehicles are the same for each style of vehicle but there are two additional actions available depending on the vehicle choosen.

  When choosing a motorbike you will have an additional option of doing a "wheelie."

  When choosing a truck you will have an additional opition of "towing" another vehicle choosen at random.


  ## Contribution
  After cloning the repository be sure to create a new branch for your feature or fix.

  ## Tests
  our modifications.

  ## Questions
  - GitHub: [bjaegerthomas](https://github.com/bjaegerthomas)
  - Email: bjaegerthomas@gmail.com