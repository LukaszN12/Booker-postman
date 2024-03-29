## :information_desk_person: About project

Project is a collection of restful-booker REST API tests performed in the Postman tool. <br>
API documentation can be found at: https://restful-booker.herokuapp.com/apidoc/index.html

## :rocket: Getting started

#### :pushpin: List of steps needed to run collection and tests 

:one: [Postman installation](#one)

:two: [Importing a file into Postman](#two)

:three: [Creating environment variables in Postman](#three)

:four: [Run collection and testing](#four)

----

#### <a name="one">:computer: Postman installation</a>

1. Go to the [Postman website](https://www.postman.com/downloads/) and click the orange button with name of your operating system.
2. Download the installation file, then run the installer and follow the instructions that appear.
3. Postman is ready to use.

#### <a name="two">:open_file_folder: Importing a file into Postman</a>

1. Go to [my Postman collection file](https://github.com/LukaszN12/Booker-postman/blob/main/Booker.postman_collection.json).
2. Click on the three dots icon in the top right corner and click "Download".
3. Run Postman and click on "Import" button in the top left corner.
4. Drag and drop the downloaded file from the Download folder into the "Import" window.
5. The collection will appear in Postman, ready for use.

#### <a name="three">:earth_africa: Creating environment variables in Postman</a>
1. Click on the "Environment" dropdown in the top left corner in Postman.
2. Click on the "New" button to create a new environment and choose "Environment" icon.
3. Give your environment a name.
4. Create a "baseURL" variable. You should enter the value "https://restful-booker.herokuapp.com/booking" into the "baseURL" variable or yoy can download and then import environment from "https://github.com/LukaszN12/Booker-postman/blob/main/Produkcja.postman_environment.json". The URL variable is named {{baseURL}}.
5. Click "Save" button to save the environment.
6. Click on the "Environment" dropdown in the top left corner and select the environment you just created.</p>

#### <a name="four">:runner: Run collection and testing</a>
1. Click on the "Collections" icon in Postman.
2. From the list of collections, select the one named "Trello - REST API" and click on the icon with three dots that appears when you hover over the collection name.
3. Select "Run collection" from the list.
4. Click right button.
5. Click "Run collection"
