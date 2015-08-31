GOOD MORNING, PEOPLE!

The proposal is for a collective game project, in #ludumdare, whose main driving idea is to be developed by anyone, have little to no direction, accept as many contributions as possible (all that are not disruptive) and go with the result in an ever increasing mess of a game.

A FEW POINTS TO BE DECIDED EARLY
--Language:
To really be inclusive and dynamic, I believe Javascript and Lua are the best options, thus, one of those must be chosen. Both have dynamic typing which is nice because with static typing you can't really patch stuff and hold them together with duct tape. Javascript is hated by some but runs in browsers which is nice. Lua is less hated and has delicious coroutines, but then again it also has 1 indexed arrays made by the devil himself. With rnlf's Motor2D Löve can be potentially used on the browser, which is nice.
With Lua, we can potentially use native stuff on the C side, good for performance, but this is only possible with the cooperation of a C guy like rxi which is unlikely. Actually the cooperation of anyone at all is unlikely but whatever

--Libraries et al.:
With Lua the most compelling choice is Löve. Löve includes sound, graphics, physics etc. without pushing a particular approach of game logic organization down your throat, which is nice.
If we go with Lua it is further recommended that we use rxi's stuff because they are cool.
With Javascript, there is no clear choice, but first of all one must chose between pure HTML5 or a varying level of libraries and abstraction. A low level is Jallegro, a high level is FlixelJs, for example. With a high level, people may not like the approach of the framework, which is off-putting. With lower level or pure HTML5, there is a chance of browser incompatibilities.
IMHO (drnick) this situation actually gives Lua an edge.

--2D/3D
2D is definitely more inclusive. 3D with 2D gameplay (Doom/Wolfeinstein-ish) could be considered, specially if graphics are mostly sprites. The balance is heavily to 2D.

--Graphics style
Frankly, there is absolutely no possibility of cohesion, so multiple styles will have to coexist side by side (photorealism, pixel art, etc). Attempts to unify the game by replacing placeholder art would be welcome.

--Perspective
Mostly the top-down vs. platformer. IMHO (drnick) top-down is a better choice because the gameplay can be more varied and because platformer physics may be trickier which could be off putting. Alternatively, both can exist simultaneously, which would be totally rad.

--Version control
Would happen on github and belong to me (drnick). I'd accept pull requests, but potentially less formal patches from people who have difficulty using git. SourceTree or equivalent would be recommended.
Builds of the game could include all earlier versions, so that the game can be seen in its progression.

--Basecode
Unless a high level game thingamabob is chosen, some basecode is necessary which can be a source of discontentment. However, do we really care if a lot of stuff ends duplicated and messy? It would also be nice if an experient contributor would provide us with his/her basecode.

--Direction
While the whole point of this proposal is to minimize direction and let it go where it wants to, it will be cooler if some cooperation happens and I think this can take place in the format of a wishlist. Wishes can include adding an inventory system, a checkpoint system, and other stuff, and I think over those there must be greater cooperation but that can definitely be worked out.
Also, all contributions which are disruptive of the project or of other people's work shall not be accepted unmodified.

--License
This is a potential subject of heated debate. Options include: GPL, MIT and the I-give-all-the-fruits-of-my-labour-to-drnick-license.

--Number of players
The possibility of online multiplayer is ridiculous, because there is around one third of a person actually willing to write networking code in all of ludum dare. However, the game can support local multiplayer. IF, AND ONLY IF, some small but significant care is taken in programming this will be possible. This is mostly to have keys be configurable, not to keep player state in globals, etc.

HOW TO JOIN
Since there isn't actually any project yet, please express your desire to participate to drnick and manifest your opinions on the points above (preferably on a text document, pastebin links favoured). We can also agree on having a IRC channel, and then I can create the repository and we can hopefully start.
I'd love the project to be happening by mid September, an arbitrary date. So, we shall organize and debate ourselves in the upcoming two weeks.

TL;DR: At least tell drnick you like this idea (if you do like this idea of course).
