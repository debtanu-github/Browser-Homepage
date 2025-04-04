# Browser Homepage

A customizable, minimalist browser homepage designed to look similar to the default Chrome new tab page but with enhanced shortcut management. Keep your most important websites at your fingertips and maintain focus.

## ✨ Features

* **Minimalist Design:** Clean interface inspired by the Google homepage aesthetic.
* **Unlimited Shortcuts:** Add as many website shortcuts as you need, breaking free from default browser limitations.
* **Quick Access:** Keep essential websites readily available to streamline your workflow.
* **Focus:** Helps you navigate directly to needed sites without unnecessary browsing or distractions.
* **Favicon Support:** Automatically attempts to fetch and display website icons (favicons) for visual recognition (uses Google's favicon service, fallback icon shown if unavailable).
* **Easy Management:** Add, edit, or remove shortcuts easily via a simple modal dialog.
* **Drag & Drop Reordering:** Organize your shortcuts exactly how you want them by dragging and dropping.
* **Local Storage:** Your shortcuts and their order are saved directly in your browser's local storage – no external account needed.
* **Search Integration:** Includes a functional search bar that performs a Google search or navigates directly to a typed URL.
* **Local Search History:** Suggests previous search terms entered *on this page*.

## 🚀 Setup & Usage

1.  **Download:** Download the `my_homepage.html` file from this repository.
2.  **Save Locally:** Save the file somewhere permanent on your computer (e.g., in your Documents folder).
3.  **Set as Startup Page (Chrome Example):**
    * Open Chrome Settings.
    * Go to "On startup" (in the left sidebar).
    * Select "Open a specific page or set of pages".
    * Click "Add a new page".
    * You need the full path to the file you saved. Right-click the `my_homepage.html` file in your file explorer, find "Properties" (Windows) or "Get Info" (Mac), and copy the full location/path.
    * **Important:** Prefix the path with `file:///` and replace backslashes (`\`) with forward slashes (`/`).
        * *Example (Windows):* If the path is `C:\Users\YourName\Documents\my_homepage.html`, enter `file:///C:/Users/YourName/Documents/my_homepage.html`
        * *Example (Mac):* If the path is `/Users/yourname/Documents/my_homepage.html`, enter `file:///Users/yourname/Documents/my_homepage.html`
    * Paste this `file:///` path into the "Site URL" box and click "Add".
4.  **(Alternative) Open Directly:** You can also just double-click the `my_homepage.html` file anytime to open it in your browser.

**Important Note on Data:** Shortcuts are saved using `localStorage`, which is specific to the address (origin) used to open the file. Shortcuts added/managed via the `file:///` path will be separate from any added/managed if you run the file via a local web server (e.g., `http://localhost:xxxx`). For consistency, use only one method (either `file:///` or a server) to manage your shortcuts.

## ⚙️ How to Use Shortcuts

* **Add:** Click the "Add shortcut" button and fill in the Name and URL in the dialog box.
* **Open:** Click anywhere on a shortcut button (except the options icon) to open the link in a new tab.
* **Edit/Remove:** Hover over a shortcut, click the 3-dot icon (⋮) in the top-right corner, and select "Edit" or "Remove" from the menu. Use the dialog box to make changes for "Edit".
* **Reorder:** Click and hold a shortcut button, drag it to the desired position among the other shortcuts, and release the mouse button. The new order is saved automatically.

