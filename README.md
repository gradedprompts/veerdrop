# Veerdrop

A match-three puzzle game with wind, in one HTML file, built by a single prompt in Cursor (Grok 4.7, medium effort).

Play it: https://gradedprompts.github.io/veerdrop/

`index.html` is the unedited output of one run of the prompt. Nothing was changed by hand after the run.
SHA-256: `f5dfeae7fce5a03c358c84b345d8a9a7b47d0b222184d06170f831c8f6efbf33`

How it plays: swap two neighbouring pieces on an 8 by 8 board so that three or more of one kind stand in a line. They clear, the pieces left are blown along and new ones blow in. Pieces do not always fall down: every level has its own order of winds (down, left, up, right), and each move is blown by the next one, shown by a yellow bar on the board's edge. Four in a line leave a ringed piece that clears its row and column. Eight levels, three stars to earn on each; your best scores and stars are saved in your browser.

Click a piece and then one beside it, or drag it across; on a phone, tap or swipe. Space starts the next level, P or Esc pauses, M toggles sound, and the keys 1 to 8 pick an open level. It needs no network at all. Add `?level=4` to the address to start a level straight away.

The prompt that built it is being prepared for Graded Prompts: https://www.gradedprompts.com/prompts/apps
