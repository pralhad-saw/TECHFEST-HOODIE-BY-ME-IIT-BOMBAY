# TechFest 30 Hoodie - How to Edit It in Figma (Complete Beginner Guide)
 
You have one file to work with:

- **`techfest30-hoodie-designboard.svg`** — the whole design board recreated as vectors: hoodie front + back, all prints, color palette, typography and garment specs. Every text is a **live text layer** and every shape is an **editable vector**, with named layers.

Figma imports SVG files as fully editable layers, so this file *becomes* your Figma design. Follow the steps below in order — no prior Figma knowledge needed.

---

## Step 0 — Create a free Figma account (2 minutes)

1. Go to **figma.com** and click **Sign up** (the free plan is enough for everything in this guide).
2. After signing in you land on the Figma home screen.
3. Click **“New design file”** (top-right area). A blank grey canvas opens. That canvas is your workspace.

Handy basics once you're in:

- **Scroll / pinch** = zoom. Press **Shift + 1** anytime to zoom so everything fits the screen.
- Hold **Space + drag** (or middle-mouse drag) to pan around.
- The **left panel** = Layers (your design's parts, like folders).
- The **right panel** = properties of whatever you clicked (colors, fonts, size, export).

## Step 1 — Bring the design into Figma

Easiest way: **drag the `techfest30-hoodie-designboard.svg` file from your folder and drop it onto the Figma canvas.**

(Alternative: open the SVG in a text editor, copy all the code, and press **Ctrl+V / Cmd+V** on the canvas.)

You'll see the full board appear. In the left **Layers panel** it shows up as named groups: `header`, `hoodie-front`, `hoodie-back`, `panels`. Press **Shift + 1** to fit it on screen.

> If a **“Missing fonts”** window ever pops up: click it and pick any font Figma suggests. The fonts I used (Space Grotesk, DM Mono, Rozha One, Grenze Gotisch) are free Google Fonts that Figma already has, so this normally won't appear.

## Step 2 — Edit any text (e.g. put your own event name on the hoodie)

1. **Click once** on a text = selects the whole text block.
2. **Double-click** = puts your cursor inside the text so you can type.
3. Change the words, then click an empty part of the canvas to finish.
4. With a text selected, the **right panel** lets you change font, size, weight, alignment and letter-spacing.

Where the useful texts live (Layers panel path):

| What you want to change | Look for layer |
|---|---|
| Board title | `header` → `header-title` |
| Front chest text | `hoodie-front` → `front-print` → `front-print-title` / `front-print-sub` |
| Big back text | `hoodie-back` → `back-print` → `back-print-display-1/2` |
| Back tagline / date / place | `back-print-tagline`, `back-print-date`, `back-print-place` |
| Coordinates & status lines | `back-print-coords`, `back-print-status` |

Tip: to reach a layer inside a group, either expand the group in the Layers panel, or **double-click** on the canvas to dive one level deeper each time.

## Step 3 — Change colors (hoodie color, print color, background)

1. Click the shape you want. (If the whole group gets selected, press **Enter** or double-click to dive deeper until a single piece is selected. You can also **Shift-click** several pieces at once.)
2. In the right panel find **Fill** and click the small color square.
3. A picker opens — at the bottom there's a **hex box**; type a code like `FF6F00` and press Enter.

Useful targets:

- **Hoodie fabric color:** `front-body`, `front-hood`, `front-sleeve-left/right`, `front-cuff-left/right`, `front-pocket`, `front-hem` (and the same names with `back-` for the back view). Select them together with Shift-click and set one Fill to recolor the whole garment.
- **Orange print/logo color:** everything currently `#FF6F00` (chest logo, star, taglines, border).
- **Board background:** the layer `board`; the orange frame is its stroke.

## Step 4 — Move, resize, duplicate

- Just **drag** anything to move it (the Move tool `V` is always on by default).
- **Drag a corner handle** to resize; hold **Shift** to keep proportions.
- **Ctrl+D / Cmd+D** duplicates the selection — perfect for making a second hoodie colorway.
- **Ctrl+G / Cmd+G** groups, **Ctrl+Shift+G / Cmd+Shift+G** ungroups.
- **Ctrl+Z / Cmd+Z** undoes anything. Don't be afraid to experiment.

To use *only the hoodie* without the board: select the `hoodie-front` (or `hoodie-back`) group, **Ctrl+C**, then paste it into any other Figma frame/poster/story.

## Step 5 — Export your finished design as an image

1. Click the board once (the big group).
2. Right panel, bottom: **Export** → click the **+** button.
3. Choose **PNG** and set scale to **2x** for a crisp file.
4. Click **Export …** and save it.

---

## About the fonts

- **Space Grotesk** — headlines/titles (free, built into Figma).
- **DM Mono** — coordinates, captions, specs (free, built into Figma).
- **Rozha One** — the big “AETHERIAL RENAISSANCE” display type (free, built into Figma).
- **Grenze Gotisch** — stands in for the blackletter sample. The original board lists **Bleeding Cowboys**, which is *not* a Figma/Google font. If you own that font: install it on your computer, use the **Figma desktop app**, select the text and choose “Bleeding Cowboys” from the font dropdown to swap it in.

## If anything feels stuck

- Can't click a specific piece? You're probably selecting its parent group — press **Enter** or double-click to dive deeper, or pick the layer directly in the left Layers panel.
- Lost your selection/zoom? Press **Shift + 1**.
- Broke something? **Ctrl+Z / Cmd+Z** until it's back.

That's the whole workflow: import → double-click to edit text → Fill to change colors → Export. You now know the four moves that cover 90% of Figma.
