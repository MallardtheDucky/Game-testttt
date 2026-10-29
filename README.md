# REPUBLIKA
A PC-only (desktop browser) political and military strategy RPG of the Philippine Revolution. This is the opening screen. New Game plays a transition into the character cards (two Political, two Military, plus a Custom Person sandbox card). Clicking a character plays a selection animation, then a black screen with a quote about their country, then an interactive journal: an open book where you write the figure's life in first person, entry by entry. The journal opens with two **Foundations** choices (how the life will be told, and the trait you carry) before the timeline begins, and a scene image fades in behind the book for each entry. Each choice is written out as a short passage, then choose the line that moves time forward to turn to the next entry; the finished page stays on the left. For historical figures one choice per entry carries a red "As history recorded" stamp; the others are different roads. Custom Person uses the same journal with no stamped path.

## Publish on GitHub Pages
1. Create a repository and upload these files to the root.
2. Settings → Pages → Deploy from branch → `main` / root.
3. Open `https://<username>.github.io/<repo>/`.

Note: while the journal is open the opening-scene animations are switched off to keep it smooth. Click the page or press Enter to finish a passage that is still being written.

## Background images
Scene art lives in `assets/backgrounds/`. 9 of the 11 scenes have art; `prison-cell.jpg` and `uprising-dawn.jpg` (later chapters) still show a coloured placeholder until their files are added. Backgrounds are dimmed in CSS (`.bg` brightness and `.bgv` vignette). See `assets/backgrounds/IMAGES_NEEDED.md` for the full list, file names, sizes and prompts. While reading the journal, press **B** to show which file the current scene uses.

## Journal writing (latest update)
- **The game now opens in 1892.** Every journal is begun in 1892 and ends with the character's belief at the close of that year. Nothing after 1892 appears in the prologue.
- Each historical figure writes in first person, like a diary kept that year: a dated opening note, then memories of birth, youth and 1892, with real details (Tondo and the Pasig, Fleming & Co., Letrán, Kawit and the island trade, Madrid and La Solidaridad). Each entry carries a place line under its year. The stamped option is still the one history recorded.
- 1892 starting positions: Bonifacio, warehouse clerk of Tondo (Rizal exiled 7 July, Katipunan founded that night); Mabini, law student and court clerk; Aguinaldo, young trader of Kawit; Luna, pharmacist in Madrid.
- Custom Person stays basic: class of birth (rich, middle or poor), then schooling and work that fit that class, then what turned you toward the cause, then your conviction. Age is counted back from 1892.
