## Hierarchy
 Server<br>
 &nbsp;&nbsp;ㄴSession<br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ㄴWindow<br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ㄴPane


## Prefix Key
 CTRL-a

## Sessions
- List Sessions: s
- Switch to last Session: S
- Attach Session w/ name completion: g
- Create Session: C
- Detach Session: d
- Rename Sessions: $
- Current pane as new Session: @
- Join marked pane to current session/window: t + secondary-key
    * Secondary-keys:
      1. h, -, ": join horizontally
      1. v, |, %: join vertically
      1. f, @: join full screen

## Windows
- List Windows: w
- Create Window: c
- Rename Window: ,
- Next Window: [
- Previous Window: ]
- Last Window: a
- Windows: 0 - 9
- Swap Windows: < or >
- Renumber Windows: Ctrl-n

## Panes
- Show Panes #'s: q
- New Vertical Pane: \
- New Horizontal Pane: -
- Toggle Panes: o
- Navigate Panes: Hold down CTRL and use VIM arrow keys (HJKL).
- Cycle Pane Locations: CTRL-o
- Zoom Pane: z
- Mark Pane: m

## Misc
- Reload tmux source: R
- Resurrect save: CTRL-s
- Resurrect restore: CTRL-r

## Plugins
- Urlview - open URLs: u
- Resurrect - Save session: Ctrl-s
- Resurrect - Restore session: Ctrl-r
- Copycat - Regex search: /
- Copycat - Simple file search: Ctrl-f
- Copycat - Jumping over git status files: Ctrl-g
- Copycat - Jumping over SHA-1 hashes: Ctrl-h
- Copycat - Url search: Ctrl-u
- Copycat - Number search: Ctrl-d
- Copycat - Ip address search: Ctrl-i
- Open - Selection with default program: o
- Open - Selection with the $EDITOR: Ctrl-o
- Open - Search selection in search engine: Shift-s
