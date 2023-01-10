# Assignment 1, WASP Software Engineering Course

The interview with Luigi Quaranta has been interesting and formative, allowing me to learn more about linters, both what they can provide and how they are developed.
Together with Luigi, we went through my habits when programming and the use of text editors, IDEs and python notebooks, especially concerning the development of AI software. In the following part, I will present my takeaways from the experience and suggestions for improving the pynblint. 

Python notebooks have become particularly popular in the developers' community, especially when dealing with the development of AI components. This could be due to the possibility of partially executing a section of the code, or by the possibility of structuring the code similarly to a text document increasing the explainability of the code. Moreover, the possibility of using remote resources for free like google colab has pushed multiple students to try this new approach. And hence, became more popular when these same students moved into the working environment. 
In my research and work, I do some AI development in the field of Deep Learning and Reinforcement Learning. However, even if I tried and used them for university projects, Notebooks never took my attention that much. I still prefer a well-documented repository with multiple and smaller files than not a notebook file. Moreover, the difficulty of easily using version control software with Notebooks in a readable way pushed me away from using this tool in my day-to-day activity. However, I found them especially useful for learning and teaching purposes allowing interactive ways of reading/testing loops and a better and easier learning experience. Has well given the possibility to integrate, in a good-looking way, a big part of texts, I think that can be a particularly good way to explain or showcase some applications (like at dev conferences).
Given that, it was initially difficult for me to test properly the pynblint tool, since I don't use Notebooks a lot. But it was immediately clear the why of the tool and especially the utility of it to the community. 
As explained above, however, even if Notebooks are not in my daily toolset, I'm quite a fan of them when dealing with learning or bootstrapping purposes. And for this reason, I have used them sometimes. 
After the first use of the pynblint tool, I thought it was a very useful tool, especially for some reason that I have encountered multiple times that can be quite annoying. 
First of all, the capability of using the "run all cells" button should always run. But often, those files are not tested carefully before being shared with others creating particular stress when dealing with them at the start of a project. However, some other features like the warning messages related to the length (in number of lines) of the code cells could be useful in some cases but can have a high variance depending on the use case. For instance, teaching material with hundreds of lines of code could be difficult to understand, but for a researcher testing a particularly long NN model could be quite normal. And even if it is just a warning, it could lead some people to change their coding style due to these suggestions. 
Additionally, this kind of warning/issue message could greatly change in importance depending on which kind of developers are going to use it. A researcher testing multiple NN models, maybe could want to define them in multiple cells but maybe not need to execute all the cells with the different models every time (or even more when they want to test different versions of the same parameters).
Some of these challenges, however, should be dealt with by the notebook format in itself, more than by a linter, and for this reason, I think that the pynblint is already very good at this stage.

I don't use Notebooks, however, I'm quite a daily user of linters and auto-completion software, and I rely on them to facilitate the development part of my job. The facility of using them with IDEs while writing code, I think, has been one of the major factors that have brought me to use these tools regularly and look for a better version of them, for example, an extension of my IDE. This lowering of the barrier entry for the usage of the tool, I think, would be essential also for the pynblint. The integration of the tool with the most used IDES/text editors, or the possibility to automatically run them on online websites like google colab, I think would greatly benefit the community of Notebook users.

Finally, I generally think that the use of linters as part of the toolset of a developer can greatly benefit and facilitate their work. However, this kind of tool would also need to be used together with other tools like debuggers to facilitate the entire development process. With particular attention to Machine Learning development, I think that this is still, in some way, challenging and that further improvement in this field will be very useful. 