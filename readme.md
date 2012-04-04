#Notely
Notely is a simple command line utility for saving short text notes.

##Installation
My preferred way of installing notely is this ``ln -s `pwd`/notely ~/bin/notely`` which
puts it in my ~/bin/ folder.

##Usage
notely add [message] - adds a note with message, opens an editor if message is empty

notely del id - deletes message with id matching the provided id

notely list - shows all notes

notely clear - deletes all notes

notely pair - starts pairing, shows you a code to type

notely pair [code] - finishes pairing, requires the code from the pair start

notely sync - syncs with the remote server
