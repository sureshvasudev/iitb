## Introduction to Google Collab interface for Python notebooks

Let's talk about the features in the Google Collab interface for Python notebooks. Here I have a Python notebook whose runtime I had recently disconnected using the Disconnect and Delete runtime button that is available under the Runtime tab, which is why wherever you can see usually the Connect option here it says reconnect.

## Reconnecting Python notebook to remote RAM and disk

So let's first reconnect this notebook to a RAM and disk which is remotely allocated. Now there are a lot of options available here.

## File menu options in Google Collab

Under the File menu, you can locate the notebook. In the drive, you can create a new notebook, you can upload a notebook, you can rename the notebook, move it, move it to Trash, save it, and so on. The other options pertain to various editing tools that are required when you write the notebook such as under edit menu you have various options like Select All Cells, Cut cell, Copy cell and so on.

## Editing tools and clearing outputs in Google Collab

There is also an important option here under the edit menu which says Clear all outputs. So this will clear every output. After that you so this will clear every output. After you have run the code. Under the view menu you can see the table of context, notebook info and so on.

## View and insert menu options in Google Collab

In the insert menu you can look at options such as creating a code cell, creating a text cell and so on. Under the runtime option, you have various options such as running all cells, running before the cells, running cells and below the cell, restarting the session, disconnect and delete runtime which I spoke about before and so on. Let's create a notebook now, or I should say, let's create a cell inside the notebook.

## Creating and executing code cells in Google Collab

So here you can see the options, one for code cell, one for text. So let's create a code cell. So here let's just have some code, very simple code, say A equal to 2B equal to three, and I want to find A+B which I will store in a variable C and I want to find A into B which I will store in a variable D To execute this cell, we can click the play or the execute button here. Or as you can see here, we can use the keyboard shortcut which is control plus enter or even shift plus enter.

## Keyboard shortcuts for executing cells

Let's execute this. When you execute the cell and it is finished executing, you will see a green tick mark here and it shows the time that it took to execute also. Now let's also see how to create cells above and below the cell.

## Creating and editing text cells in Google Collab

So if you just hover your mouse pointer above the cell, you will see two options, code and text. Similarly, when you hover your mouse pointer below the cell, you will again see the same two options. Let's create a text cell or a markdown cell. Above our code cell. It says here double click or enter to edit. Now when you go inside the text cell for editing, you can see all the standard text styling and editing options are available to you such as bold, italics, and so on. And additional tools are also available, such as formatting text as code bullets and so on. So for instance, let's say let's take two variables A&B and find their sum and product.

## Formatting text in markdown cells

So this is what we want to do. I have written it in the markdown cell, so I just need to shift, enter or close the cell and you will see that the text is displayed here. Let's go back inside and edit some of the formatting of the text that we have written. So suppose I highlight A and click on the bold button. You can see that Google Collab has used the command double* before A and after A. This makes this letter bold for italics. You can also highlight B and click this button here. Or you could just use* and*. So here you get an italicized B and if you close the cell you can see what that looks like.

## Creating headings and subheadings in Google Collab

Let's add another text cell above this one and enter that. So here I want to say a heading. Now you can see if you just write heading, it shows as normal text. To display this as a heading, you need to use a hash. If you use 1 hash, as you can see here, it displays as a big heading. So let's just close that cell. As you can see, the heading is displayed here. Let's change the word of the heading, let's call it Python.

## Organizing code with headings and subheadings

So the heading for this section is Python. And you can see there's an arrow here, which you can use to collapse or expand the cells under this heading. Let's create another text cell below this section. So let's have another heading here, say addition. Now within this section, let us move this line C equal to A+B. Let us cut it and paste it here because this is addition. Let's create another text cell and have another heading here which is product. Similarly, maybe I can call this sum and under product, let's create a code cell and move the product command that is D equal to entropy into the product header. So now you can see there are three headers Python sum and product and each has its own markdown that is text and it has some code cells.

## Using table of contents for navigation

On the left side you can see that there is this option table of contents. So as you can see here the headings are appearing in the table of contents. The word Python, here it is. It is highlighted on the left if you click it on the right. If you choose sum, then it will take you to that section of your code. So as you can see, using headings and subheadings is very useful. Now here I have Python And sum and product.

## Collapsing and expanding sections in Google Collab

These are three headings. Let's put sum and product inside the Python section as subheadings. To do that you just need to change the level of the heading inside the text box. So now I am using two hashes. The moment you do that, you can see on the left side sum is now part of Python. This is the heading and this is the subheading. Similarly, I can put two hashes for product. The left side you can see now sum and product are both inside the heading Python. So now when you collapse Python, all of it with whatever is inside the section under the heading Python will be collapsed. And you can directly play it here or you can expand and then play one by one or execute 1 by 1. So this is a very useful way of organizing your notebook, organizing your code, organizing your analysis or your machine learning model code, So on.

## Working with files and temporary disk in Google Collab

Also note that there is a folder here which says or an option here which says files. If you click this, it says sample data. Now essentially this is a temporary disk that has been assigned here. So when we did the connection, we saw that a RAM and a disk has been assigned. The RAM is of course for computations and things like that. The disk is for storage and the same disk is something here. You can see it is written here disk right? So if you want to work with files, you will either have to load files into this temporary disk or you will have to connect your Google Drive to this notebook. There are separate commands to connect your Google Drive to the notebook and after that you can directly access files, that is read and write files from your Google Drive.

## Connecting Google Drive to Google Collab notebook

If you do not want to do that, if you are doing some kind of temporary analysis, you can just upload the data into the temporary memory and then you can access the file from the temporary memory using the according commands.

##  Uploading data to temporary memory for analysis

So as you can see there are various features available in Google Collab which makes it very efficient and very easy for conducting good data analysis.
