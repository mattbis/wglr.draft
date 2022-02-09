# draft - refactored libre dollop 
#### no order here, thinking out aloud 

update the current depths and combine the interesting developments.. refactored-dollop; the only thing that is now necessary is types around how commands are sub translated. FOr the moment it just will do the initial stuff.. 

writing a parser and lexer or a translator that has adapters is an intersting thought... and maybe a typescript only part....

This project too is gonna be one file probably !! hahah I forget how much I used to love working on one file for ages, never running it and then it works.. 

# deps
I have bits of 3 projects in mind vector original stuff, a recent project i noticed that did it well, the line stuff somebody did recently.. and the previous arch.. 

# todo
0. for the msmeo tool we can use teh same github actions infrastructure, and this is like a testbed, for the tool ( since its going to be a lot more complicated compiler wise etc ... potentially the engine, llvm etc + difficult libraries and code in c/c++/rust etc )
1. are the deps kinda okay to use, without including too much
2. if not should they be static deps ( most likely - the release cycle for the project is very very very slow ) so its gonna be a build include
3. i actually found the best version that wasnt the extreme - rewrite too much version
4. extract whats needed
5. combine with teh original version + the extender
6. job done , this one is out of the way and I can get back to something else

# regl
1. he might have used regl.. I might just take abit of that code, and do my thing to it.. since well its boring just using other people stuff.. lets make it harder to read! and all crazy wherever possible.... working on graphics is a lot of fun since everything is different.. You can worry about micro optimisation and write really horrible looking code.. so much fun!
