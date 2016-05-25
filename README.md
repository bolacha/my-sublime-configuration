### Sublime Plugins and Configuration

- DockBlockr - https://packagecontrol.io/packages/DocBlockr

- ConsoleWrap for JS - https://packagecontrol.io/packages/Console%20Wrap%20for%20js

```
{"keys": ["ctrl+shift+q"], "command": "consolewrap"}
```

- Bracket​Highlighter - https://packagecontrol.io/packages/BracketHighlighter

- Emmet - https://packagecontrol.io/packages/Emmet

- HTML5 - https://packagecontrol.io/packages/HTML5

- LESS - https://packagecontrol.io/packages/LESS

- Random Everything - https://packagecontrol.io/packages/Random%20Everything

- SublimeLinter - https://packagecontrol.io/packages/SublimeLinter
- Sublime​Linter-json - https://packagecontrol.io/packages/SublimeLinter-json
- Sublime​Linter-jshint - https://packagecontrol.io/packages/SublimeLinter-jshint

```
npm install -g jshint
```

- Sublime​Code​Intel - https://packagecontrol.io/packages/SublimeCodeIntel
`
{
  "codeintel_scan_exclude_dir":["node_modules/"],
}
`

- Color Highlighter - https://packagecontrol.io/packages/Color%20Highlighter


### Changes 

Package Control Messages
========================

Emmet
-----

  Thank you for installing Emmet -- a toolkit that can greatly improve your workflow. Note that this plugin automatically downloads and installs PyV8 binary (see status bar message). 
  
  ******************************
  Please restart editor 
  to finish installation process 
  after PyV8 was downloaded.
  ******************************
  
  Tab key handler
  ==========================
  
  By default, Emmet allows you to expand abbreviations with Tab key in HTML, XML, HAML and CSS/SASS/LESS/Stylus documents. As a side effect, you can’t use some of your ST2 snippets.
  
  Please read https://github.com/sergeche/emmet-sublime#tab-key-handler about how Tab handler works and how to tweak its behavior to match your needs.
  
  Enter key
  ==========================
  
  In HTML and XML documents, Emmet overrides Enter key to insert formatted line breaks between opening and closing tags. In some cases it will break character input (for example, in Japanese language).
  
  To disable Enter key handler, simply add the following option in your user's Preferences file:
  
  "disable_formatted_linebreak": true
  
  Actions shortcuts
  ==========================
  
  Emmet has a number of actions with keyboard shortcuts that may override ones you're using commonly (for example, Ctrl-E or Ctrl-Down). Please read the project main page to get list of available actions and keyboard shortcuts and how to disable them:
  https://github.com/sergeche/emmet-sublime
  
  Documentation and examples:
  http://emmet.io
  
  ------------------------------
  Follow me on Twitter: @emmetio
  ------------------------------


SublimeLinter
-------------

  
    ____        _     _ _                _     _       _
   / ___| _   _| |__ | (_)_ __ ___   ___| |   (_)_ __ | |_ ___ _ __
   \___ \| | | | '_ \| | | '_ ` _ \ / _ \ |   | | '_ \| __/ _ \ '__|
    ___) | |_| | |_) | | | | | | | |  __/ |___| | | | | ||  __/ |
   |____/ \__,_|_.__/|_|_|_| |_| |_|\___|_____|_|_| |_|\__\___|_|
  
  
  Welcome to SublimeLinter, a linter framework for Sublime Text 3.
  
                   * * * IMPORTANT! * * *
  
          SublimeLinter 3 is NOT a drop-in replacement for
          earlier versions.
  
          Linters *NOT* included with SublimeLinter 3, 
          they must be installed separately.
  
          The settings are different.
  
                  * * * READ THE DOCS! * * *
  
  Otherwise you will never know how to install linters, nor will
  you know about all of the great new features in SublimeLinter 3.
  
  For complete documentation on how to install and use SublimeLinter,
  please see:
  
  http://www.sublimelinter.com
  
  
                   _   _      _       _
                  | | | | ___| |_ __ | |
                  | |_| |/ _ \ | '_ \| |
                  |  _  |  __/ | |_) |_|
                  |_| |_|\___|_| .__/(_)
                               |_|
  
  
  Hundreds of hours have been spent writing and documenting SublimeLinter
  to make it the best it can be — easy to use, easy to configure,
  easy to update, easy to extend. If you use SublimeLinter and feel
  it is making your coding life better and easier, please consider
  making a donation to help fund development and support.
  
  To donate: https://github.com/SublimeLinter/SublimeLinter3#share-the-love
  
  Thank you!


SublimeLinter-json
------------------

  SublimeLinter-json
  -------------------------------
  This linter plugin for SublimeLinter provides an interface to json.
  
  For more information, please see https://github.com/SublimeLinter/SublimeLinter-json.


SublimeLinter-jshint
--------------------

  SublimeLinter-jshint
  -------------------------------
  This linter plugin for SublimeLinter provides an interface to jshint.
  
  ** IMPORTANT! **
  
  Before this plugin will activate, you *must*
  follow the installation instructions here:
  
  https://github.com/SublimeLinter/SublimeLinter-jshint


SublimeCodeIntel
----------------

  SublimeCodeIntel
  ================
  
   ____        _     _ _                 ____          _      ___       _       _
  / ___| _   _| |__ | (_)_ __ ___   ___ / ___|___   __| | ___|_ _|_ __ | |_ ___| |
  \___ \| | | | '_ \| | | '_ ` _ \ / _ \ |   / _ \ / _` |/ _ \| || '_ \| __/ _ \ |
   ___) | |_| | |_) | | | | | | | |  __/ |__| (_) | (_| |  __/| || | | | ||  __/ |
  |____/ \__,_|_.__/|_|_|_| |_| |_|\___|\____\___/ \__,_|\___|___|_| |_|\__\___|_|
  A full-featured code intelligence and smart autocomplete engine for Sublime Text.
     (Code intelligence plugin ported from Open Komodo Editor to Sublime Text)
  
  
  +-------------------------------- HELP WANTED ---------------------------------+
  |     Maintaining this project is hard, I do it in my spare time, but I'm      |
  |     basically all alone. If anyone is interested in contributing, please     |
  |     contact me. I really need much more help maintaining SublimeCodeIntel    |
  |                                                                              |
  |                       Follow me on twitter @germbravo                        |
  |           You can find us at #sublimecodeintel on irc.freenode.net           |
  |                                                                              |
  |             If you like SublimeCodeIntel, please make a donation:            |
  |        http://sublimecodeintel.github.io/SublimeCodeIntel/donate.html        |
  +------------------------------------------------------------------------------+
  
  
  Features
  --------
  
  Supports all the languages Komodo Editor supports for Code Intelligence (CIX, CodeIntel2):
  
  JavaScript, Mason, XBL, XUL, RHTML, SCSS, Python, HTML, Ruby, Python3, XML, Sass, XSLT, Django, HTML5, Perl, CSS, Twig, Less, Smarty, Node.js, Tcl, TemplateToolkit, PHP.
  
  
  Provides the following features:
  
  * Jump to Symbol Definition - Jump to the file and line of the definition of a symbol.
  * Imports autocomplete - Shows autocomplete with the available modules/symbols in real time.
  * Function Call tooltips - Displays information in the status bar about the working function.
  
  
  + Shortcuts for jump to definition have changed:
  
    For Mac OS X:
      * Jump to definition = ``Control+Click``
      * Jump to definition = ``Control+Command+Alt+Up``
      * Go back = ``Control+Command+Alt+Left``
      * Manual CodeIntel = ``Control+Shift+space``
  
    For Linux:
      * Jump to definition = ``Super+Click``
      * Jump to definition = ``Control+Super+Alt+Up``
      * Go back = ``Control+Super+Alt+Left``
      * Manual CodeIntel = ``Control+Shift+space``
  
    For Windows:
      * Jump to definition = ``Alt+Click``
      * Jump to definition = ``Control+Windows+Alt+Up``
      * Go back = ``Control+Windows+Alt+Left``
      * Manual CodeIntel = ``Control+Shift+space``
  
  
  
  Notes
  -----
  
  ** Restart Sublime Text after reading this **
  
  
  More information
  ----------------
  Please take the time to read the documentation:
  
  In case of trouble, please read the Troubleshooting section in the README.
  
  * Online - http://sublimecodeintel.github.io/SublimeCodeIntel/
  * Git - https://github.com/SublimeCodeIntel/SublimeCodeIntel
  
  
  IMPORTANT
  ---------
  
  Do NOT edit the default SublimeCodeIntel settings. Your changes will be lost
  when SublimeCodeIntel is updated. ALWAYS edit the user SublimeCodeIntel settings
  by selecting "Preferences->Package Settings->SublimeCodeIntel->Settings - User".
  Note that individual settings you include in your user settings will **completely**
  replace the corresponding default setting, so you must provide that setting in its entirety.
