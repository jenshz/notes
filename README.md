# notes

Make note-taking fun again!

Install these tools for maximum enjoyment:

* silversearcher-ag
* ruby
* grip

## Usage

Open todays notes in your favorite text editor (as long as your favorite text editor is Sublime Text):

    ./notes

Open yesterdays notes (e.g. the latest notes before today):

    ./notes -1

Open some time earlier (e.g. 2 days ago):

    ./notes -2

Open an entry in "grip" for previewing

    ./notes grip <entry>

Remember to commit your notes once in a while:

    ./notes commit

With silversearcher you can search through your notes like this:

    ./notes search <keyword>

To add a global shortcut to bash, add the following fragment to your .bashrc:

    function notes {
        (cd ~/path/to/notes; ./notes $@)
    }

NB: If you don't like to use sublime as your default text editor (I don't know why you wouldn't?!), you can customize this in the ./notes script.
