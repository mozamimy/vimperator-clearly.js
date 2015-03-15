# vimperator-clearly.js

A simple vimperator plugin for Evernote Clearly.

## Requirement

- Latest Firefox
- Vimperator 3.0+
- [Evernote Clearly](http://evernote.com/clearly/)

## Installation

Put plugin/vimperator-clearly.js to `~/.vimperator/plugin` directory.

## Usage

You can toggle Evernote Clearly window by using following command.

```
:clearly
```

If you want to use as keyboard shortcut,
put following line into your .vimperatorrc.
This example assigns 'e' key to toggle.

```
nnoremap e :clearly<CR>
```

## Progress report
- [x] Toggle page
- [ ] Save directly via Evernote Clearly from an web page

## Contributing

1. Fork it ( https://github.com/mozamimy/vimperator-clearly.js/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
