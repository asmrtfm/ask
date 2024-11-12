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
>   (*) Trailing args always comprise QUESTION (escapes are interpretted).
>
>   -h,--help   show this helpful usage information
>
>   -y,--yes    fail if answer is not (y|yes)
>
>   -n,--no     fail if answer is not (n|no)
>
>   -l,         repeatedly ask [<QUESTION>] until a desired response is given.
>    --loop     the desired response can be set using the (`-y`|`--yes`) and (`-n`|`--no`) flags,
>               (default is (y|yes) )
>
>   -s,         ask [<QUESTION>] again if a response
>    --strict    other than (y|yes) or (n|no) is given
>
>   -p,         write the user's response to STDOUT
>    --prompt   (deactivates all other options)
>               (causes `ask` to function as a simple read prompt)
>               (optional: ` --prompt=MESSAGE `)
>
>```
