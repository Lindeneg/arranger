## Kanban Board

---

Arranger allows creation of Boards, Lists, Cards and Checklists. Lists and Cards are draggable while Checklists may become so in the future. Different color-themes can be set for individual Boards while this feature may be implemented for Cards as well.

The app works as intended but the code is quite the mess, especially state-management. I made some questionable early on which proved to be unwise. Albeit it works as intended, the code could be much more elegant, so this app will likely receive an overhaul at some point.

---

Build from source or try it [here](https://arranger.lindeneg.org/).

Clone source

`~/$ git clone https://github.com/lindeneg/arranger && cd arranger`

Initialize submodule

`~/arranger$ git submodule init && git submodule update`

Install packages

`~/arranger$ yarn install`

Start backend (in dev mode)

`~/arranger/server$ yarn dev`

Start frontend

`~/arranger/client$ yarn start`

---

![boards](https://github.com/Lindeneg/arranger/blob/master/examples/boards.png)
![board](https://github.com/Lindeneg/arranger/blob/master/examples/board.png)
![card](https://github.com/Lindeneg/arranger/blob/master/examples/card.png)
