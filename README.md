# FireNote
Online Markdown Notebook - backend with Firebase

## Editor.md

This work is based on [Editor.md](https://github.com/pandao/editor.md), just extend a cloud storage function with Firebase realtime database and storage.

![feel and look](https://vgy.me/BQ27ht.png)

## Usage

### Create new note

After login with your Google acount, you can create new Markdown notes in "File -> New".

![new note](https://vgy.me/B2UdSY.png)

Give your note a name, and set a "notebook" where the note stores ("Default Notebook" if not specified).

### Save the note

Click "File -> Save" or just use your keyboard with "ctrl+s" to save (or update) the note.

### Open existing note

Click "File -> Open" or "ctrl+o" will open a modal that let you choose the note you can open.

## Make yours

For this repository and update the Firebase setting in "assets/script.js":

```js
var config = {
apiKey: "<your firebase project apikey>",
authDomain: "<your firebase project domain>",
databaseURL: "<your firebase project database url>",
projectId: "<your firebase project id>",
storageBucket: "<your google cloud storage bucket url>",
messagingSenderId: "<your sender id>"
};
```

All the parameters can get from your Firbase console panel.

Please ignore the code style in the `script.js` and make yours :stuck_out_tongue: ...