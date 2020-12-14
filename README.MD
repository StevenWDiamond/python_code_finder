# PYTHON CODE FINDER
### Author: Steven Diamond
### Last Updated: 12/14/2020

## Overview
The purpose of this project is to create a searchable database that can be used by Python users to find information and code that they are searching for. Users make a series of choices to find what they are searching for and the notebook will return one or more of the following:
* Information (can be cut/pasted from notebook)
	- Example: *the properties of a List*
* Code (can be cut/pasted from notebook)
	- The code pattern is shown.
	- If applicable, markdown is used in the code to specify how the user would adapt for their code.
	- For some outputs, below the code/markdown, notes are provided.
* Visuals (delivered outside of the notebook)
	- For code producing searches, these show how it would look in a Jupyter notebook.
	- For information that requires tables, etc., these are given instead of information printed in notebook.

## Current Project Status
The prototype in this notebook is operational and does work for a limited scope of outputs. To try it out, choose Cell > Run All and follow the prompts. To get to some real examples of output, I recommend that you start by choosing Python Info/Code followed by Math Functions. This area is fully written/coded.

## Next Steps
There is much to be done to finish this project, but much of this is really more of the same.
* For the Python section, we need to write information/code for several of the options and think through other options that may not be included at this time.
* For the Numpy and Pandas sections, we need to think through what needs to be included, create a branched system for users to read what they want and then create the output materials.

The section that will take the most work (but maybe be the most useful) is the Data Visualization Builder. Our vision for this is a section where you would choose a type of visual (i.e. histogram) and then choose the types of extras that you want to include (i.e. legends). We intend to use all caps for things that you would replace with your own information (i.e. X/y variables, labels, etc.).

By the end of 2020, we will be doing two things:
1. Completing a single type of Data Visualization for demonstration purposes.
2. Finishing the remainder of what is currently planned for the Python section

Long-term, I would like to partner with web designers/coders to put this on the internet. In the interest of time, it is currently a purely Python project. Unfortunately, there are limitations to this method but we have tried to make it as friendly as possible.

## Help If You Want/Can
In the short-term, there are two ways that you can help with this project:
* The easiest way to help is with your opinions/suggestions.
	- Let us know what you think by emailing us at bwood.consulting@gmail.com.
	- Try out the sequence Python Info/Code > Math Functions > Addition to see an example where we both give code and an PNG file example. We are curious to hear what you think of this – should we give both or just the code?
	- What sections would you like to see beyond Python, Pandas and Numpy?
	- For the Python section, did we miss something that you want included?
	- For Pandas and Numpy, do you have any specific requests (and code, if you have it)?
* The other way to help has to do with the notebook itself – things that we know could be improved but which we haven’t had the time to explore.
	- The application begins with a welcome message that is up for 5 seconds so you can read it. We would love to have this not come up when the user chooses to restart.
	- Each time, the application asks for input, we have added 20 spaces and the question and response box appear onscreen. You may notice that, when the list of possible responses is long, the status and/or the first few options are not completely viewable. The user can scroll up but we would love to have it so that the beginning of the block is at the top of the viewable area.
	- We have designed this to run directly in Python. We did try to run in in the Terminal app but that does not allow for inputs. If you know of another medium where the application might look better, please let us know.

### Thanks again for your interest in our application – you can contact us at bwood.consulting@gmail.com.
