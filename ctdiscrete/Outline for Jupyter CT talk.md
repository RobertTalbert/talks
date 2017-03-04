Goals: Audience members should be able to describe CT, frame problems in discrete math as CT problems, explain how coding in Jupyter helps CT 

## Outline

+ Welcome and introductions
+ CT and DM
	+ In discrete math we don't want students to learn merely facts but also processes, and they do this by solving problems and answering questions 
	+ DM is different because many of its problems and questions are about computation, or about reasoning about computation, or can be answered through computation. 
	+ Example: How many subsets does an n-element finite set have? 
		+ Decompose the problem by doing pieces: 2 elements, 3, 4, 1, 0
		+ Look for patterns in the pieces
		+ Form an _abstraction_ that precisely phrases the pattern
		+ Then (the hard part) devise a way to explain why your abstraction is always true. It's a proof, but proofs in DM are often algorithmic in nature. (Example: Standard proof is a recursive algorithm for actually constructing the subsets.)
+ Computational thinking
	+ This four stage process describes what we call _computational thinking_
	+ Popularized by Jeanette Wing
	+ Goes back to Seymour Papert and constructivism
	+ In Papert, CT is closely tied with using the computer -- as a tool for thinking
	+ Using the computer is still a good way to think computationally. We do this all the time in math using CAS's like Maple and Mathematica for calculus, or Geogebra for geometry; what's an appropriate tool for CT in discrete math?
+ Jupyter 
	+ It is a graphical notebook-based interactive environment for computing in a variety of platforms 
	+ Used to be called iPython but it's not just python any more 
	+ Free and open source and available for local install and in the cloud (e.g. SageMath Cloud) -- runs in a browser (fire one up running Python 3) 
	+ Cells
		+ Code cell -- Execute a hello world and a Python list comprehension 
		+ Markdown -- Enter in some formatted text with links, tables 
		+ LaTeX -- Enter in as usual
	+ Combines text, latex, and executable code 
	+ Can switch to other platforms, like Sage or R
	+ Can export to PDF, HTML, etc. for sharing and submission
	+ Advantages over CAS's like Maple or Mathematica: FOSS, non-proprietary environment, used by real scientists, uses Python which is more frequently used beyond the course (and IMO is simpler). 
		* Cons: No symbolic computation (easily) 
+ How I use in my classes
	* Students learn python through self paced study -- just the basics 
	* We then use python:
		- In demo mode to set up group activities
		- As part of group activities where students work in pairs or fours to write code to investigate a question (decomposition) and come up with a conjecture (pattern finding and abstraction)
		- For extended "challenge problems" involving programming or just writing code snippets 
+ Examples of use 
	+ Number of edges/number of nodes (Python using the networkX and Matplotlib libraries -- could also use Sage)
	+ Testing relations for properties (straight Python) -- raised interesting questions
+ Conclusion -- CT works well with DM and students can use computers as a means of constructing the things they are studying. Jupyter makes this interactive and professional. The medium is the message. More details at the website and at jupyter.org.



## Brain Dump


Many of the questions and problems in DM are questions about computation or reasoning about computation. Maybe enumeration. 

- Combinatorics 
- Logic 
- Induction -- recursion 
- Graph algorithms 

Example: How many subsets does an n element set have? 
Answer: 2^n

Decompose the problem into smaller ones: Try it on 2-, 3-, 4-, element sets
Pattern recognition: 4, 8, 16,...
Abstraction: It seems to always be 2^n. 
Solution design: Need to prove this somehow. Standard induction proof is really an algorithm that shows how to recursively construct the sets themselves (computation). 

This four-stage process is often referred to as computational thinking

- Jeanette Wing popularized
- It goes back to Seymour Papert and constructionism/constructivism -- using the computer as a tool to think with

CT makes a good framework for learning DM and corresponds to Polya's problem solving methods. 

-----

Using the computer as a tool for thinking in DM: 

+ Makes decomposition simpler, easier to generate large numbers of examples 
+ Large data sets from decomposition make it easier to notice patterns and form abstractions
+ Insofar as solution is algorithmic, writing computer code forces precision and handling of details. Don't really understand an algorithmic process until you try to build it. 

-----

A tool for using the computer as a tool for thinking: The Jupyter Notebook

+ Graphical interactive front end for computation
+ Formerly "iPython" notebooks; now rebranded because different environments can be run using the same notebook
+ Notebooks run in a browser 
+ Combines executable code, Markdown, and LaTeX in the same place
+ Free and open-source -- sources and download links on the website 

Frame DM problems in computational terms and have students submit Jupyter notebooks with math, text, and code that document the entire life cycle of the solution process. 

Examples:

+ Writing Python code to test properties of relations
+ networkX library to experiment with graph properties (number of edges/number of nodes) 
+ itertools to test counting rearrangements 

--- 



To learn more... website 



