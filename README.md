# How run javascript code on android?

Lets start web development on android assuming you know 
the syntax and have 3 months of coding practice in more 
popular programming languages such as html css and javascript 
makes this tutorial easy.

For this demo will be using javascript to run simple app using 
command Line. It's up to you to take leap of faith in android 
dev.

Here are the requirements
- An internet browser
- An android device with version 7 and above

What you will achieve
- Managing a projects
-Installing packages
-Bonus a lil work wont hurt getting a web server 
running and displaying the output in the browser

Enough said get your feet wet download termux.

https://www.google.com/url?sa=i&source=web&cd=&ved=2ahUKEwjj1OCTovjqAhUKzaQKHWQKCmQQ3YkBegQIARAE&url=https%3A%2F%2Fplay.google.com%2Fstore%2Fapps%2Fdetails%3Fid%3Dcom.termux.api%26hl%3Den_US&psig=AOvVaw2lQ9QD-lWVcHLHQL5cNFYm&ust=1596311567506681

# 1) Managing a projects
You will need to make a work enviroment
after downloading installing and opening we can now 
comfrim we on the same page.

$

Then will need create a folder called "web-dev" and 
set its directory using these commands.

$mkdir web-dev
$cd web-dev

This $mkdir command will make a folder in the home 
directory called web-dev and to set 
the path to "/data/data/com.termux/files/home/web-dev" 
we used $cd command which is very important step so 
dont skip it otherwise your server will get confused 
where to get and host the files from.

Once the directory has been set ,we need write and 
save our documents for that you can the use the 
vim package. This will be your text editor go ahead and 
install.

$pkg install vim

Wait for it to download to finish and press Y when prompt 
to save it, we then install nodjs for powering our server. 
Nodejs will be heart of most of our projects. Go ahead and 
install nodejs

$ npm install nodejs

after the node package is installed we can server javascript 
files by writing code go ahead and open up vim.


$vim app.js

We can now fill data inside the "app.js" document press i on the 
keypad to insert ,a variable wages with some values with lil math 
in this the code to hmm. 

var wages = 1000 *8; //some math
console.log("your name"); //enter your name
console.log("amout: $" + wages);//prints your wages

Hit ESC and type :wq to save and closes the Document . Now run the app.js command

$ node app.js

wonderful you get output of yourname and the amount.

Ready for some more magic

# 2). Running a Web server
So you need to display output in the browser. open the link 

https://github.com/codewizz999/samples/blob/master/sample-server.js

in a separate window and copy sample server source 
code in to your app.js remember to save press ESC :wq 
very important after that run.

$node app.js 


# Test in your app in browser.

Copy this address port in the search bar-> http://localhost:8080/
and then paste it in the browser search it you should get output: "hello, world!" 
in the browser if dont know how the code works iv provide link at the end otherwise
if you did get the output your're done congrats you finished the demo. 

# Conclusion
In practice we have learn how to manage projects by creating a javascript document in folder called web-dev used terminal commands access packages paths , we displayed output your name and amount variables.

and bonus We then copied javascript server code from my github repo which displayed hello, world! in the browser these where basics for getting started.

But thats not the end this demo was to show you that it possible to use localhost to make projects on android and tweak test your apps visuals before the final launchs.

One More thing if you like more tutorials like these please like my page on facebook to be alerted on newer ones.

Need more brain read more info about nodejs can be found here's in the link i promised you 

https://nodejs.dev/learn


If you've finished this tutorial leave me a message.
email: balandinosalex@gmail.com

keep coding amigos.

