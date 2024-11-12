# ask

**USAGE:**
>        `ask [<OPTIONS>] [<QUESTION>]`
>

**SYNOPSIS:**
>        Prompt the user with an ostensibly yes-or-no QUESTION (all input is optional).
>        Returns 0(true) for (y|yes), or 1(false) for (n|no).
>        If no QUESTION is provided it will simply prompt for a '(Y/n)' response.
>        Response is case-insensitive.
>

**OPTIONS:**
>```
>   (*) OPTIONS must precede QUESTION if supplied.
>
>   -h,--help      show this helpful usage information
>
>    -y,--yes      fail if answer is not (y|yes)
>
>     -n,--no      fail if answer is not (n|no)
>
>   -l,--loop      repeatedly ask [<QUESTION>] until a desired answer is given.
>                   the desired answer can be set using the (`-y`|`--yes`) and (`-n`|`--no`) flags,
>                    or defaults to (y|yes)
>
>     -s,           ask [<QUESTION>] again if a response
>      --strict      other than (y|yes) or (n|no) is given
>
>```
