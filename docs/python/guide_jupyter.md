## Introduction to Jupyter Notebook Interface

Let's talk about the Jupiter notebook interface in a little bit more detail. Here are all the various options that you have with which you can edit and manipulate the behaviour of your Python notebook.

## File Options in Jupyter Notebook

Under file we have new notebook. You can open a file from a folder, make a copy of the file, save the file differently with a different name, rename the file, so on and so forth. Since we already have a notebook open, let's move on to the next set of options.

## Cell Operations in Jupyter Notebook

So here you can see there are various options, cut cells, copy cells, delete cells, undo, delete cells, so on and so forth. A cell is nothing but this box that you can see here in which you can write a piece of code. Let's write a piece of code so that we can see how to work with it.

## Writing and Executing Code in Cells
I am going to write a very simple code say A equal to 2B equal to three and C is A+B and D is A into B. So I have written 4 statements or 4 lines in one cell. Now you can execute the cell and check out other behaviors under the cell option or the cell menu here. So you have various options like running the cells, running all the cells, running all cells above a cell, so on and so forth. You can also look at the type of the cell.

## Running Cells and Execution Order

So by default, the cell we have is a cold cell. You can convert that into a markdown cell as well. Markdowns are typically used for writing text, showing equations and so on, showing equations and so on. Now let's execute this cell. Now you can see there is a play button which says run which essentially runs this cell. Let's click it. As you can see the cell has been run and you get a number here.

## Printing Values and Using Shortcuts

One. When you execute this cell the second time, this number will go to two. So let's execute this cell again run. So as you can see, it has gone to two. Now suppose in the next cell which by default has been created, when you execute 1 cell, I want to print the value of C&D. So let me first print C again. We can click run and it is going to output the value of CC is AB, that's 2-3 which is five. Now you can also run a cell using a shortcut, a keyboard shortcut Shift and Enter. So let me put D here and use Shift and Enter to execute the new cell. So I can see here D the value of D has been output which is 6. You can restart your notebook as well. So if you go under kernel you will see various options here such as interrupt, restart, restart and clear output, restart and run all reconnect and so on.

## Restarting Kernel and Clearing Output

South let's restart and clear the output. So when you restart and clear the output, what will happen is all the previous execution will be deleted. So all the temporary values in the memory and everything like that will be deleted and the output also will be cleared. So in fact, here you can see five and six. These are the output. At the same time C&D, the values are stored in memory as well. So let's go ahead and restart and clear the output. As you can see, it says kernel ready and all the numbers, all the execution numbers are gone. Now we can execute all the cells from this cell.

## Managing Cells with Shortcuts

If you just click this button here which says restart the kernel, then rerun the whole node. If you just want to run every cell, you can go into cell and then click run all. So let's run all the cells. So as you can see the number has restart from 1-2 and three. So this was one cell executed, second cell, third cell. There are other options available as well, such as creating the cells between or above or below cells. There are shortcuts for a lot of these. So for instance, suppose I select the cell which says 2. I could insert a cell above or a cell below. So you can click this option here to insert a cell above. You can also use the shortcut Escape and then A. So here if you see it says A to access this option you have to use the escape. So if I click this cell and then say escape A, you can see that a new cell has been created above this cell. Escape B creates a new cell below this cell. Similarly, we can delete the cells also. The option for that is Escape DD which you can find under edit here. So if you press escape and then DD, it will delete the cell. You could click it from here. Typically it is better to get used to the shortcuts. So let us delete all these cells, escape DD, and then you can keep clicking DD to delete all those cells.

## Interrupting Kernel Execution

There are of course other important options too, such as interrupting the execution of the kernel. This is usually important when you write a piece of code which may not be the most optimal piece of code and and you just want to check how the code is executing and if it's running into trouble, then you do want to interrupt it so that you can save your time. As such, these are some of the basic features in the Jupiter notebook and there are many other features here that can be explored.

## Exploring Basic Features of Jupyter Notebook

One important feature is the type of cell. So let's create a cell above the code cell and here you can go to cell cell type and change it to a markdown. Now what happens is you will see immediately that the execution number or the area for the execution number has gone because this will not be executed. This is now only text. So there will be no Python execution of whatever is written in here. So here we usually write things which support the code. For example here I can say for example here I can write.

## Markdown Cells and Text Formatting

Let us consider 2 variables A&B. As you can see it shows up as text. Let me create another cell just below this one but keep it as a code cell. Now if I say let us consider 2 variables A&B and execute it, Python or Jupiter will tell me that there is an error because what I have written here is not understood by Python. This is not Python code, so we typically use text in the markdowns. Now what if we want to make A&B look better? So there are various options in markdown such as if I put a between two* symbols and B then that makes the letters italic. I can even make them bold. So using two* symbols will make them bold. I can even convert these into headings. So if I use 1 hash then it becomes heading number one. If I use two hashes it becomes heading #2 and so on. Heading #1 looks like this. Let me create another markdown here and say we want to find A+B and A into D and let us put this as heading #2 like this.

##  Combining Markdown and Code Cells in Jupyter Notebook
So you can see this is the bigger heading, this is the smaller heading. So typically a Jupiter notebook would be a combination of these markdowns and code cells, which explains the Interactive Data analysis or machine learning model that the notebook is executing.
