# fun
templates &amp; about page

## how it works
Write blog post in md. Then run pandocs using code below 

`pandoc -s --template template.html "file.md" -o "file.html" --lua-filter=remove-ids.lua`

