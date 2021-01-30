The idea is to collect people choices for replacement of
various commands in machine readable format.

Using the data it will be possible analyze command history to
propose lifehacks and time savers.

### problem

There are already too many things-awesome, but no database 
that can be used to lookup and upgrade your habits to new
frontiers automatically.

### `evolve.txt`

Here I tried to record:

1. if I use Ctrl+R in bash to lookup history, then `hstr`
project can save my time
2. TBA

The goal also is to explain other people why there is `hstr`
in my dotfiles. dotfiles do not hold this connection. I can
put comments and write `README.md` docs, but that will not be
machine readable and people will not be able to **compare
reasons across repositories**.

The current format is detected by the first line:

    # evolution: techtonik.1

And that's should be enough to move it to the next version.
`techtonik` is my name, and `evolution` is my repository with
the file named `evolve`. It has `.txt` extension to render and
edit easily.

Feel free to evolve and change the format. There is no spec.
What you see is what you get. Just make sure that there is a
path from the old dataset to a new one.

What matters is ability to evolve, not standards. This should
be maximized. And if I put this right, tools will be able to
evolve from `techtonik.1` to your next format, and evolve how
do we change our habits too.
