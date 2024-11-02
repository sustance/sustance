I’m @sustance, interested in *nix, luatex, shells, Lua, python, smol web

#______TRAVEL BOOK______

- a  All pdfs for a single name prefix (trip) for the first day af travel on that trip

- b  Get PDFs of all ticket and in target folder with names YYYMMDDi-* where "i" sets sequence within date.

- c  run: incpdfTravel.lua 20241210 YYMMDD <-- for trips to include in this book
--> Script 1-*.sh does this

- d  Cut and paste that output to NextTickets.tex 
    NOTE This can be automated but this should enable the book to be recreated without keeping a cpy)

- e  Compile NextTickets.tex with LuaTeX
    NOTE this will give a random number of pages and must be still be adjusted to fit 8 page signatures
-->  Script 2-*.sh does this

- f  Compile signaturesX8.tex
--> Script 3-*.sh does this

<!---
sustance/sustance is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
