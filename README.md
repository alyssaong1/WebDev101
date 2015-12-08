# Compsci 345 A3 Documentation

We will go through the various tools that will help you through Assignment 3. These tools act as a guideline - you need not follow it exactly, but it is what we recommend you use as best practice for your assignment.

## Table of contents

- [Compsci 345 A3 Documentation](#compsci-345-a3-documentation)
	- [Table of contents](#table-of-contents)
	- [Digital Wireframing](#digital-wireframing)
		- [1. Pencil Project (recommended!)](#1-pencil-project-recommended)
			- [Linking pages](#linking-pages)
			- [Installing extensions](#installing-extensions)
			- [Creating your own collections](#creating-your-own-collections)
		- [2. Mockingbird](#2-mockingbird)
			- [Linking pages](#linking-pages)
			- [Like grids?](#like-grids)
			- [Exporting your wireframes](#exporting-your-wireframes)
		- [3. Invision](#3-invision)
		- [Also check out...](#also-check-out)
	- [Building out your HTML pages](#building-out-your-html-pages)
		- [1. Atom](#1-atom)
			- [Adding a new or existing project](#adding-a-new-or-existing-project)
			- [Adding packages to Atom](#adding-packages-to-atom)
			- [Other text editors worth mentioning](#other-text-editors-worth-mentioning)
		- [2. Bootstrap](#2-bootstrap)
			- [Adding Bootstrap to your project](#adding-bootstrap-to-your-project)
			- [Using Bootstrap in your webpages](#using-bootstrap-in-your-webpages)
			- [Customizing Bootstrap styles](#customizing-bootstrap-styles)
		- [3. Colour schemes](#3-colour-schemes)
		- [4. jQuery plugins](#4-jquery-plugins)


## Digital Wireframing

You will have created paper wireframes in your previous assignment - this is an example of low fidelity wireframing. Digital wireframing is considered to be of higher fidelity, which will help you further solidify the form and function of your website in the design process. Here are a list of some tools you can use:

### 1. Pencil Project (recommended!)

Pencil Project is an open source wireframing tool that allows you to create wireframes for desktop and mobile apps. It's completely free to use - [download it here](http://pencil.evolus.vn).

In the left pane there are collections of stencils you can use for web and mobile wireframing. There are also  stencils for you to create diagrams. You could also use these to annotate your wireframe with notes. The top pane allows you to customize the stencils you insert.

![pencil-main](img/pencil-main.png)

#### Linking pages

Pencil allows you to link buttons to other pages to show the interaction and flow in your website. Right click the button you inserted into the canvas, then click on *Link to*. You can then choose which page the user will be navigated to when clicking the button.

![pencil-link](img/pencil-link.png)

However, you'll only be able to interact with the wireframes once you've exported it as a html page. To do this, go to *Document > Export Document...* Select the output to be **Single web page**, then hit continue.

![pencil-export1](img/pencil-export1.png)

Select which pages you wish to export, then continue. Click on *Browse...* and choose which folder you want the html page to be saved in, and make sure "Copy links from background pages" is ticked. Hit done.

![pencil-export2](img/pencil-export2.png)

Now, browse to the folder you saved it in. There should be a newly created html page. If you open the html page in your browser, you should see the wireframes you made all in one page. Try clicking on the buttons in your wireframes and it should navigate to the different webpages like you specified earlier.

#### Installing extensions

Pencil also allows you to install [additional collections](http://code.google.com/p/evoluspencil/downloads/list?q=label:Stencil) and [additional export templates](http://code.google.com/p/evoluspencil/downloads/list?q=label:Template). First of all, simply download the zip file of the extension you'd like. Let's use the Font Awesome collection as an example.

![fa-zipdl](img/fa-zipdl.png)

If you want to install a collection, go to *Tools > Install new collection...* in Pencil. If you want to install an export template, then go to *Tools > Manage Export Template...* in Pencil.

![pencil-tools](img/pencil-tools.png)

Select the zip file you just downloaded, and Pencil should automatically add in the collection/template, like this:

![pencil-facollection](img/pencil-facollection.png)

#### Creating your own collections

What if they don't provide the stencil you're looking for? No worries - you can add your own custom stencils in Pencil! Pencil can take an image file and turn it into a stencil that you can use in your wireframes. Let's say I'm making wireframes for a map app, and I wanted to add some stencils, e.g. a map and a location icon. Go to *Tools > Developer Tools > Stencil Generator..*. Drag your image file(s) into the listbox, and enter a name, short description and author for your collection. You can remove the website if you wish. Hit continue.

![pencil-collgen1](img/pencil-collgen1.png)

Make sure all the images are checked, then hit done.

![pencil-collgen2](img/pencil-collgen2.png)

Choose a location to save the zip file - this is the installation file for the collection of stencils you just made. Now, go to *Tools > Install new collection...* and select the zip file that was just generated. Your custom collection should now be added to the pane on the left (collections are ordered alphabetically), and you can now use the stencils you just uploaded.

![pencil-collgen3](img/pencil-collgen3.png)

### 2. Mockingbird

Mockingbird is a HTML5 app for creating wireframes, meaning that everything is done in your browser and no installation is needed. [Take me to Mockingbird](http://gomockingbird.com). You can only have one project at a time with the free version, but otherwise it is a neat wireframing tool with no restrictions on the number of stencils and pages you can create in that project.

On Mockingbird you can create many pages for your webpage wireframes. Start wireframing by dragging and dropping the controls in the left panel into your pages. Some cool features include adding comments on the wireframe and sharing the wireframe with others for collaborative editing.

![mb-home](img/mb-home.png)

#### Linking pages

To link buttons to pages in Mockingbird, you can double click on the button, click on *Link to page* and select a page you want the button to link to. Hit Preview to test the linking out.

![mb-link](img/mb-link.png)

#### Like grids?

You're in luck - Mockingbird happens to have grids as well. Click on the Settings icon (the cog) in the bottom pane, hover over columns, then select the number of grid columns per page you'd like.

#### Exporting your wireframes

Click on the Settings icon in the bottom pane, and hover over *Export*. You can either export your wireframes as a PDF or PNG. The downside of this is that your wireframes are no longer interactive (i.e. button navigation no longer works), but not to worry - Invision is here to help!

### 3. Invision

If you feel like the linking tools in Pencil weren't good enough, or you have screenshots of wireframes but don't know how to link them, then [Invision](http://invisionapp.com) is your best friend. It's completely free, and it'll turn those screenshots into interactive wireframes (a.k.a. click dummies).

After creating an account, click on the plus (+) sign and give your prototype a name and type. We'll be using Desktop (web) for the purposes of this assignment, but as you can see, you can also use Invision for mobile apps and even watches!

![inv-createproj](img/inv-createproj.png)

You'll need to upload the screenshots of your pages separately. If you need to split a PDF file into separate wireframe pages, [here's a tool you could use](http://smallpdf.com/split-pdf).

![inv-proj](img/inv-proj.png)

Click on one of the uploaded screens, then just click and drag on the screen to create hotspots.

![inv-hotspot](img/inv-hotspot.png)

These hotspots are basically the areas of interaction in your webpage. After creating a hotspot, you can specify a page it navigates to. Alternatively, you can also specify a certain point on the same screen that the hotspot will jump to when clicked. Hit P to go into preview mode and test those hotspots out!

![inv-preview](img/inv-preview.png)

### Also check out...

- [Balsamiq](http://balsamiq.com) - Free for the first 30 days, then you have to buy a license to save your work. You could screenshot the wireframes you make in Balsamiq to get around this. Otherwise a great wireframing tool with community-created stencils you can add.

- [Moqups](http://moqups.com) - Another HTML5 app for wireframing. The downside with Moqups is that the free version does not allow you to export your wireframes. Again you could get around this by taking screenshots of the wireframes you make in Moqups.

- [Creator Ionic](http://creator.ionic.io) - Very handy tool for creating interactive mobile wireframes!

## Building out your HTML pages

After creating your digital wireframes, it's good to build it out to see what your designs actually look like when applied to html pages. Here are some tools to help you create your html pages and develop your designs:

### 1. Atom

You may be wondering what to use to write all your code in. Well, it all starts with the atom. No literally, it does. [Atom](http://atom.io) is an open source text editor made by the folks at GitHub, and we recommend you use this to create your webpages. It's lightweight, powerful and extremely easy to use.

#### Adding a new or existing project

To start a new project, go to *File > Open...*. Navigate to where you want your new project to be saved, then create a new folder. This new folder is where all your files for the project will be stored. Select your newly created folder, then hit ok.

To add an existing project, do the same steps, except instead of creating a new folder you can just select your existing project folder.

You should see your folder (with any existing files) in the left hand pane. Click on the various files to view and edit them.

![atom-ide](img/atom-ide.png)

#### Adding packages to Atom

Being open source, Atom has awesome extensibility thanks to the work from other developers. We can easily add packages to Atom should we require additional functionality. To access the Atom settings pane for Macs, go to *Atom > Preferences...*. For Windows,... Click on the "Packages" tab - here you can see all the existing packages you have preinstalled packages that come with Atom. Click on the "Install" tab to start searching for packages online and installing them.

As an example, let's say we want to install a package that allows us to run our html file in many different browsers straight from Atom. To do this, we could install the [open-in-browsers](https://atom.io/packages/open-in-browsers) package. Open the Atom settings pane, go to the "Install" tab (as described above) and search for "open-in-browsers".

![atom-install](img/atom-install.png)

Hit install and that's it! Now, if you right click any html file in the left pane, you'll see the *Open in browsers* option which lets you run the html file in the browser of your choice. Check out all the packages [here](https://atom.io/packages) and have fun exploring!

#### Other text editors worth mentioning

- [Sublime Text](http://sublimetext.com) - One of the most popular, easy-to-use text editors out there. The only downside is that you'll have to pay for the full version.

- [Visual Studio Code](http://code.visualstudio.com) - Fun fact: VS Code was built on Atom.

### 2. Bootstrap

Bootstrap is a mobile-first front-end framework that will make responsive web development a breeze. Long story short, it'll instantly help make stuff look pretty when you insert elements into your webpage, and help you add some really cool functionality to your webpage. You won't be allowed to use templates though.

#### Adding Bootstrap to your project

To add Bootstrap to your project, head over to their [homepage](http://getbootstrap.com), click on Download Bootstrap, then click on Download Bootstrap again.

![bs-dl](img/bs-dl.png)

After unzipping, copy the contents of the bootstrap folder and paste it into the root of your project folder. We then need to reference the relevant scripts within the head tags of our html file, like this:

```html
<head>
  <link rel="stylesheet" type="text/css" href="css/bootstrap.css"/>
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
  <script src="js/bootstrap.js"></script>
</head>
```

Note that Bootstrap has JavaScript plugins, and as such, jQuery is needed for these to work. Thus, we need the second line. You may also have a different folder structure depending on where you pasted the contents of the bootstrap folder - reference bootstrap.css and bootstrap.js according to your folder structure.

#### Using Bootstrap in your webpages

Luckily, Bootstrap provides great documentation on their webpage and has lots of community support. To see how Bootstrap is applied, let's try making a button to start off.

Insert the following line of code in the body tag of your html file:
```html
<button type="button" class="btn btn-lg">Large button</button>
```
Run your html file in your browser. Your button should look something like this:

![bs-btn](img/bs-btn.png)

By adding classes, Bootstrap provides us with styles that we can apply to our button - no longer do we have the ugly default html button. For more Bootstrap button customizations, view the documentation [here](http://getbootstrap.com/css/#buttons). Scroll through the documentation to see the customizations you can apply on other elements too.

#### Customizing Bootstrap styles
It's highly likely that you'd want to use your own colour scheme, borders and fonts for your website elements. The good news is, we can customize Bootstrap's styles by overriding the CSS classes with our own styles. As an example, let's try customizing the colour and border of the large button we made.

First of all, let's make a CSS file called "custom.css". This is where all the customization for the Bootstrap styles will go. To customize the button, we need to figure out which part of the CSS needs to be changed. If you right click the large button (in your browser) and click "Inspect Element", a pane appears that lets you see the styles that are being applied to the selected element. You can modify CSS in the pane itself to see your styles being applied in real time. [Here](https://www.youtube.com/watch?v=3zSUIm1KrPs) is a video showing you how you can do this.

Let's try making the background of the button a different colour in the Inspect Element CSS pane. As you can see, the colour is coming from the background-color attribute of the .btn-primary class. We can either change the background-color attribute in the .btn-primary style directly, or we can add a background-color attribute to the .btn-lg class and override the default style by Bootstrap.

![inspectel](img/inspectel.png)

You should be able to see the colour of your button changing on the spot as you modify the background-color attribute in the inspector. Now that we've identified the classes that affect the colour of the button, we need to override these in our custom.css file.

Go back to your code, and copy and paste the following snippet into the custom.css file:
```css
.btn-lg{
  background-color: #5C2D91;
	color: #FFFFFF;
}
```
In this snippet of code we made the background color of the button purple, and the button font white. Run the html file in the browser and you should see that the button now looks like this:

![bs-modified-btn](img/bs-modified-btn.png)

But what if you only wanted to change the colour for one particular button without affecting the styles of all other large buttons you add into your website in future? To do this, you can attach an id to the button in the html file, then modify the background colour by selecting the id from the css. So your html code for the button would look like this:
```html
<button type="button" class="btn btn-lg" id="myPurpleBtn">Large btn</button>
```
And your css for that particular button would look like this:
```css
#myPurpleBtn{
  background-color: #5C2D91;
  color: #fff;
}
```
The styling is now unique to that button.

### 3. Colour schemes

Every website should have a colour scheme. Picking the colour scheme can be a bit of a challenge, but fortunately we've got some tools that will get you started.

#### Adobe Color CC

[Try it out!](https://color.adobe.com) Adobe Color CC allows you to pick your colour scheme based on colour rules, like analogous, monochromatic and complementary. After you select a colour rule, try dragging the circles on the colour wheel around - the colour palette automatically readjusts itself according to the colour rule you selected.

#### Paletton

[Try it out!](http://paletton.com) Paletton also lets you pick your colour scheme based on colour rules, but with more customization and control available. Hover over the various colours and shades in the square palette to view their hex codes.

- TODO: insert annotated image of how to use paletton

### 4. Storing data

It is extremely common for websites to take in user input and store it, and chances are you'll want to do this for your website too. To bypass all the complications of setting up a backend to store our data, we recommend you use client side storage called **localStorage**. With localStorage, websites can store data locally in the user's browser. More outdated browser versions may not support localStorage - [check this link out](http://www.w3schools.com/html/html5_webstorage.asp) to see if your browser version supports it.

You may be thinking - what if I close my browser, or clear my history or clear my cache? Does this mean all the data in localStorage will be wiped out? The answer is **no**, your data will still exist in localStorage if you close your browser window, and our data will be stored with no expiration date. So the data will still be there a day, week, month and even a year later.

#### How to use localStorage

Using localStorage is easy. Everything is done by calling methods on the **localStorage** object in JavaScript. localStorage stores data in name/value pairs. For instance:
```javascript
localStorage.setItem('favouriteflavour', 'vanilla');
```
has the name 'favouriteflavour', with the value 'vanilla'. If we want to retrieve this data from localStorage, we would need to call the getItem method, like this:
```javascript
var myfavouriteflavour = localStorage.getItem('favouriteflavour');
```
The variable myfavouriteflavour would be 'vanilla'. Lastly, if you want to delete this item from localStorage, we would have to call the removeItem method, like this:
```javascript
localStorage.removeItem('favouriteflavour');
```

#### Working with JSON objects in localStorage

What if we want to store objects which have many attributes each, e.g. a "user" object has a name, date of birth, email address, etc. To address this, we can use JSON to represent our objects. If you are unsure of what JSON is, [read this](http://www.w3schools.com/json/json_syntax.asp). However, one limitation with localStorage is that you can only store strings - so if you tried to store a JSON object into localStorage it wouldn't work. To get around this, we can convert our JSON objects into strings first, then store it in localStorage. Let's use our "user" object mentioned earlier as an example:
```javascript
var user = {
	name: "John Smith",
	dob: "12/07/1990",
	email: "jsmith@hotmail.com"
}
```
We have created a "user" object, and it is currently in JSON format. To convert our "user" object into a string, we use the JSON.stringify method on the user object. Overall, the code to convert our object into a string and save it into localStorage would look like this:
```javascript
localStorage.setItem('user', JSON.stringify(user));
```
If we need to retrieve the JSON object from storage, we retrieve the string, then convert it back into JSON format using the JSON.parse method:
```javascript
// Retrieve string from localStorage
var userString = localStorage.getItem('user');
// Convert string to JSON format
var user = JSON.parse(userString);
```
This only stores one "user" object though. What if we wanted to store multiple user objects? To do this, we could save an array of JSON objects. If you've never worked with arrays of JSON objects before, read the JSON Arrays section of [this link](http://www.w3schools.com/json/json_syntax.asp). Our array of users would look something like this:
```javascript
var users = [
	{
		name: "John Smith",
		dob: "12/07/1990",
		email: "jsmith@hotmail.com"
	},
	{
		name: "Ben Jones",
		dob: "21/06/1993",
		email: "bjones@hotmail.com"
	}
]
```
Here we have an array containing 2 user objects, but you can add as many users as you'd like to the array. You can even have one object in the array. We would then store this array in a similar way to storing JSON objects. We convert it into a string before storing it, like this:
```javascript
var usersString = localStorage.setItem('users', JSON.stringify(users));
```
To retrieve our JSON array, we would do the following:
```javascript
// Retrieve string from localStorage
var usersString = localStorage.getItem('users');
// Convert string to JSON format
var users = JSON.parse(usersString);
```

### 5. jQuery plugins

jQuery plugins are a quick and powerful way to add more functionality to your website and make them more beautiful. These plugins are written by other developers and are usually open source, meaning you can freely use them in your website. The developers of these plugins usually write pretty good documentation on how to use the plugin in your website.

Check out some cool jQuery plugins:
- [Sweetalert](http://t4t5.github.io/sweetalert/) - Your alerts will never look boring again with Sweetalert.

- [Tubular](http://www.seanmccambridge.com/tubular/) - Want a youtube video as your background? Check this one out.

- [Tooltipster](http://iamceege.github.io/tooltipster/) - What about some cool looking tooltips?

There are thousands of jQuery plugins out there. After you design the functionality needed for your website, do a search for an existing jQuery plugins you could use to implement those functionalities. Note that some browsers don't work very well with jQuery plugins.

As an example, let's try implementing the sweetAlert plugin into our website. Go to the [Sweetalert homepage](http://t4t5.github.io/sweetalert/) and download using "Method 3: Download the sweetAlert CSS and JavaScript files". Unzip the file, and in the folder you should see a bunch of other files. The only files you need are the ones in the **dist** folder. Copy the dist folder, and paste it into the root folder of your project. For clarity, I've renamed dist to sweetalert.

![swal-1](img/swal-1.png)

![swal-2](img/swal-2.png)

Reference the CSS and JavaScript files for sweetAlert in your html file, like this:
```html
<link rel="stylesheet" type="text/css" href="sweetalert/sweetalert.css"/>
<script src="sweetalert/sweetalert.min.js"></script>
```
When you reference the CSS and JavaScript files, make sure the file paths are correct (i.e. where you pasted the sweetAlert files) - it may not be the same as ours. Let's create a button that triggers the sweetAlert when clicked. In your html file, add the following in your body tags:
```html
<button type="button" onclick="showalert()">Show me the alert!</button>
```
The line above adds an onclick listener to our button, meaning that when the button is clicked, the showalert function will be called. Now let's write the showalert function in JavaScript (our click event handler). To do this, we'll add a new JavaScript file to our project folder. A quick way to do this in atom is to right click the left pane (where you see all the files), then click *New File*. We will call it index.js. You can name it anything you like, so long as it ends with .js to indicate a JavaScript file. Then, reference the newly created JavaScript file in the html file, something like this:
```html
<script src="index.js"></script>
```
Again, make sure you use your own file path. For our example, let's use the success message sweetAlert. As shown in the documentation, copy and paste the following lines of code into the newly created JavaScript file.  
```javascript
function confirm(){
  swal("Good job!", "You clicked the button!", "success");
}
```
Here, we've created the confirm function that displays the sweetAlert. Run the html file in a browser, and click on the button. The sweetAlert should pop up. The sweetAlert homepage has documentation that shows tons of other kinds of sweetAlerts you can use - have fun exploring!
