# Ankimin

**Ankimin** is a collection of **beautiful, minimal card templates** for Anki. These themes are designed to be clean, distraction-free, and elegant – allowing you to better focus while revising.

This fork simplifies the templates to a standard template which can be used easily with any card type and which switches light and dark themes automatically, following the OS light or dark mode. 

![Ankimin Basic Card](https://github.com/ctrlaltwill/Ankimin/blob/main/Demo%20Images/Basic-Preview-Back-Plus-Ankipedia.png)

Each folder in this repository corresponds to a different card-type and contains:
- A **Front** template (`CARDTYPE-front-template.html`)
- A **Back** template (`CARDTYPE-back-template.html`)
- A **Styling** file (`CARDTYPE-template-styling.css`)

Use these to create your own themed note types in Anki.

## How to Create a New Card Template in Anki

1. **Open Anki**
2. Go to **`Tools` > `Manage Note Types`**
3. Choose an existing note type or click **`Add`** to create a new one (it may be easier to duplicate a previous similar card-type – Basic, Cloze or Image Occlusion)
4. Select the note type and click **`Cards…`**
5. You’ll see three fields:
   - **Front Template**
   - **Back Template**
   - **Styling**

## Using an Ankimin Theme

To apply a theme from this repository:

1. Open the folder of your chosen theme 
2. Open the three files:
   - `basic-front-template.html`
   - `basic-back-template.html`
   - `basice-template-styling.css`
3. Copy and paste:
   - The contents of `basic-front-template.html` → into the **Front Template** field
   - The contents of `basic-back-template.html` → into the **Back Template** field
   - The contents of `basic-template-styling.css` → into the **Styling** field
4. Add your front and back text and {{template}} content into the relevant areas of the template html (look for the `<!--- ADD FRONT OF CARD HERE -->` sections.
5. Click **`Save`** in Anki
6. Repeat for other card tips e.g. `Basic`, `Image Occlusion`

## Customization Tips

- Preview your cards as you make changes
- You can tweak colours, spacing, or fonts in the `style.css` file

## Notes

- Always **save** your changes before exiting
- Consider **backing up** your card-types before applying a new theme

## Screenshots

#### Basic Card – Front ![Ankimin Basic Card](https://github.com/ctrlaltwill/Ankimin/blob/main/Demo%20Images/Basic-Preview-Front.png)



## Acknowledgements
This fork is very lightly amended from the original and excellent [Ankimin](https://github.com/ctrlaltwill/ankimin) design by **William Guy**. It largely reflects my own preferences but the automatic light/dark mode alterations may be sufficiently useful for others to gain some benefit. Much of the changes were made using Claude, with some tweaks done 'by hand'. 

Ankimin is built upon and inspired by the excellent work of **Deshai Pranav** and his [Prettify](https://github.com/pranavdeshai/anki-prettify) framework. 

