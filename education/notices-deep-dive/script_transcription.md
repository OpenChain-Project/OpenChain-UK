## Notices Deep Dive


# Graphical In-Program Documentation

For an executable application that has a graphical user interface (such as a Windows application or a mobile application) and it contains open source, you can normally find the open source information, the licensing and notices, underneath the
"help" or the "about" menu.

_[open google chrome]_

Here we're looking at Google Chrome, and if I select "help" "about Google Chrome".

_[select "about", "google chrome"]_

You'll see that this brings up the "about page" for it.

_[go to bottom of page]_
If we go down a little bit to the bottom and we can see this copyright statement and that Chrome is an open source project and this link to other open source software.

So if we click on that.

_[click on "open source software"]_

Here it brings up all of the information of different licenses which are in this particular application, so we can show the license.

_[click on a random component name to expand to show sub-component license information]_
 
This is done very well actually. So it's giving the name of the component, you can see the license and there's even a link to the home page of that particular subcomponent source code.

If we go down to the bottom, see if we have something interesting to see.

_[go to bottom of page]_

At the bottom here we have a zlib. Open that up.

_[click on zlib]_

We can see the standard zlib licensing information.

If we go up a bit and I think we'll find webkit. I'm guessing that webkit will actually have quite a lot of licenses which are in that.

_[go up and select webkit component to expand license information]_

Let's see.

Lots of different stuff is in the webkit component part of the Chrome browser.
This is quite a nice way of doing it, but it's still fairly typical.


# Command Line In-Program Documentation

Here's an example of how an executable could display the open source notices and licenses.

_[open "command prompt" in windows]_

I'm within the Windows command prompt at the moment. I'm going to run a Python executable
program that's installed on this machine.
_[type python <return>]_

So its already given me some things which I might be able to look at here.

From it's command line, I can do copyright and it shows some fairly
basic copyright statements
 _[type "copyright" <return>]_

I can also type "credits", and it shows simple credits and where
we could go for more information.

_[type "credits" <return>]_
 
 Finally let;s try "license".

_[type "license" <return>]_
 
Now we've got full licensing information for Python, so license for itself. And also you'll see here that it's giving the
licensing information for any subcomponents that it's using. So from other open source initiatives.

_[tabbing down through the screen of displayed information]_

what do we have down here? A few interesting ones perhaps.

So here we have the bzip2 licensing information. So Python must be using that. This goes on for several pages for all of the different sub components.

_[continue tabbing down to the end]_

So there we have an example of a command line display notices.

#Distribution (hosted) Source/Executable Example

 I use an open source based text editing tool. This is where the project sourcecode is hosted - on GitHub here. 
 _[Using a web browser go to github.com/notepad-plus-plus/notepad-plus-plus project page]_
 
 It's called Notepad++.
 And you can see in here, along with the source files and information, there is a license file here.
 
 _[Open file called LICENSE]_
 
 We can see it's a GPL licensed project.
 
 Although the source is here and if I distributedthe source, then the license would go with it. It is also possible to get Notepad++ as a precompiled binary install, which I will show you now.
 
 _[open notepad++ application]_
 
So here is the executable Notepad++ running on my machine. It was installed by our IT department from a downloadable package.
 
Let's have a look what information we can find here. Let's check under notepad++ "about".

_[select menu "?" then "about notepad++" - opens information window]_

And here we see a link to the project's website as well as a summary and web reference to the full license.

_[swap to a file explorer window at the application install location]_

So now we're looking in the file explorer and looking at the install location of Notepad++. And here is the actual application executable itself and here is the uninstall script.
 
And here we see we have a license file, a file that is called LICENSE, which we will now open up into Notepad++ itself.

_[open file LICENSE in notepad++]_

Back in the application again, and here is that file.
And you'll notice that it is in fact the same license file that was on the GitHub project that we saw earlier.

So the license for Notepad++ the open source program, was distributed with the whole install script and install package itself.
