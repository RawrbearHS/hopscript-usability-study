# Hopscript: Usability Study (v1)

Written by Rawrbear	

--------

## Marketing and Usage Study

### Product Analysis

- Hopscotch is:
	- A coding app for kids to make games, stories, art and more! (Front page pitch)
	- Designed for kids 10-16, for any skill level
	- A fun creative outlet for kids
	- An educational learning resource to help build and nurture kids' coding abilities
	- Created by Samantha John and The Hopscotch Team
	- Backed by subscription and pay-to-play models
	- Uses an entirely block-based model
	- Modding capabilities are made in JS and provided from proprietary open-source tools
    - Hopscotch is targeted towards a mobile user base, with containerized JS sharing support for desktop

- Text coding is a broad field of many languages with awesome technological possibilities
- Hopscotch is a creative platform, utilizing code to create visuals
- Currently, not much allows for code to JSON conversion, besides in-app programming and low-level hacking, like the project builder. Some projects use these hacks and many others don't.

### Competitive Analysis

This section may be useful if we decide to compete with, or use concepts from other languages that may be similar.

- Scratch:
	+ Helps young people learn to think creatively, reason systematically, and work collaboratively - essential skills for life in the 21st century. (About page pitch)
	+ Designed for kids 8-16, but used by people of all ages
	+ A fun creative outlet for kids
	+ An educational learning resource to help build and nurture kids' coding abilities
	+ Created by MIT scientists
	+ Backed by donations
	+ Uses an entirely block-based model
	+ Modding capabilities are made in React and JS
	+ Scratch is targeted towards a desktop user base, with HTML5 mobile support
	
- Processing:
	+ A flexible software sketchbook and a language for learning how to code within the context of visual arts. (Front page pitch)
	+ For students, artists, designers, researchers and hobbyists who use Processing for learning and prototyping (Front page)
	+ Primarily for visual art, rather than games, storytelling or other interactive mediums
	+ Likely designed for older users
	+ Textual language: C-like syntax with varying complexity between projects
	+ Lots of learning resources
		+ Documentation includes a language reference, libraries and IDE usage
		+ Plenty of video tutorials for using Processing, made by a variety of different people on the internet
		+ Lots of code examples too, and a separate section for books on using the language
	+ You can create libraries for Processing to extend the use cases within the language
	+ Processing is targeted towards desktop users primarily, but there is a closely tied variant called p5.js that works closely to Processing and supports the web
	
- p5.js:
	+ A JavaScript library for creative coding, with a focus on making coding accessible and inclusive for artists, designers, educators, beginners, and anyone else! (Front page pitch)
	+ Meant for visual art/drawing, and has support for audio, input, video and webcam, but not really meant for games
	+ Designed for a broad audience, including beginners
	+ Textual language: built on JS, with simple syntax
	+ Introduces the programmer with a tutorial, and then transitions into learn/examples pages, as well as video resources
	+ You can extend off the core library of p5.js to create additional code libraries
	+ p5.js is targeted towards the web; you can use it to make projects that work in desktop and mobile web browsers
	
### User Analysis

Feedback from https://forum.gethopscotch.com/t/you-can-talk-about-your-hopscotch-coding-here-27-official/60976/9158?u=rawrbear
If you responded to that, thank you very much!

- The impression of text coding, from users on the Hopscotch forum:
  - Feels like a "professional" graduation from block coding
- Misc feedback:
  - Lack of undo/redo feature limits the editor
  - Math scrolls all the way to the right in one line, with a lack of word wrap
  - Some people here have started to use Unity and/or Blender
- I asked forum members a couple of questions to answer. Here are the results:
	+ "Why do you love, like or dislike Hopscotch programming?"
		* Very flexible coding environment, where you can create a variety of types of projects
			- Freedom to play with code
		* It's very easy to use the editor and its blocks
		* Very intuitive blocks, and there are lots of them
			- You start in a visual canvas comprised of all your objects
			- Lack of documentation thereof
			- Very easy to work with clones
		* There are/were so many cool projects made on the platform
		* Making projects helps you grow with your knowledge of code
		* Blocks are drag-and-drop and always take effect, preventing syntax errors or annoyances
		* Lots of premade character assets
		* However, the editor can be somewhat limiting with its time-consuming tiny adjustments and its copy/paste features
		* Lag-related problems
	+ "Do you code with text languages, or have you ever considered coding with text languages? If so, what got you interested, and if not, what would interest you to try a text language?"
		* The majority of users who are familiar with textual programming are learning, or currently use, JavaScript
		* Programming languages are powerful to use compared to Hopscotch, allowing for complex possibilities
			- More useful features in other languages	
				+ Sounds, functions, lists, etc.
		* You can use them to make browser-based or standalone apps on many devices
			- Better cross platforming and accessibility capabilities from other languages
		* Programming languages have more real-life purpose
		* Hopscotch interested one user to branch out to web programming
		* One respondent said they were interested in textual coding because it's their knack
		* One respondent was interested, but was eventually unmotivated to learn a new programming language
	+ Is there a part of Hopscotch coding that just goes over your head? (ie. math, advanced features, struggling to making a certain type of project, etc.)
		* The answer to these, if provided, were limited to specific domains. Developing with some of these can be aided with a library. For example:
			- Game psychology
			- Music/complex melodies
			- Math in general
			- Platformers
			- 3D rendering
			- A combination of many of these
	+ "What’s your favorite way to learn new things about Hopscotch? Do you use tutorials, or do you prefer to learn on your own, and how?"
		* Some users are self-taught, and/or like to experiment with blocks
		* Others like to refer to other projects for code examples
		* Some prefer to ask questions to other people for code help on the forum
		* One respondent gets an idea and then realizes they need new skills to make it

### Conclusion: Derived Philosophy

From this information, here is a basis for Hopscript's language's syntax, purpose and market:

**Hopscript must be an intuitive, approachable, easy, enriching and feature-packed language for all users.**

Hopscript should be a language that is extremely intuitive, with syntax that is very easy to handle for all users, for the purpose of wide community adoption and minimizing opportunity costs. Syntax, tools, documentation and other means should be utilized to aid with mentally visualizing code that is being written. Syntactical structure paradigms must be straightforward and lack confusion, demonstrating the principle of least astonishment, so that even newer programmers can approach the language and see what is happening with the code, and how. Some unavoidable features like syntax errors and typos must be fine-tuned to push users forward faster when making programs. To establish Hopscript for power-users, the language must extend upon Hopscotch's features and provide further functionality, such as functions and arrays.

-------

## Requirements

Here's how this goal can be accomplished:

- Clean, easy to use syntax, optimized to be even easier than other OOP languages
- Easy to understand code structure that preferably gets close to how Hopscotch structures code, for an easy transition to Hopscript
- Clear distinction between Hopscript and other languages' usability
- Documentation and help resources clearly describe how best to transition to using text syntax and code structuring

As @anisotr0py stated, we've previously brainstormed how best to implement an **object oriented** programming language, for the purpose of additional features, such as:

- The addition of Hopscript user-created libraries
- Project Builder preset support
- Raw JSON import (not discussed yet; this is just an idea)

The language must also be versatile enough to  these additional custom features:

- Typed variable system
- Message, custom block and custom rule tracking/management
- Functions and macros
- Lists and/or arrays

To form the syntax and create a paradigm, I'd like to propose taking the following languages as inspiration:

- Python; very easy to use, object-oriented and similar to Hopscotch's type system
- JavaScript; the language of the web that many Hopscotchers already know
- Tosh; remarkably simple syntax for fast code brainstorming, albeit with poor module and code organization