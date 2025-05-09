# pamflip

> Flip or rotate a PAM or PNM image.
> More information: <https://netpbm.sourceforge.net/doc/pamflip.html>.

- Rotate the input image counter-clockwise for a specific degree:

`pamflip {{[-r|-rotate]}}{{90|180|270}} {{path/to/input.pam}} > {{path/to/output.pam}}`

- Flip left for right:

`pamflip {{[-lr|-leftright]}} {{path/to/input.pam}} > {{path/to/output.pam}}`

- Flip top for bottom:

`pamflip {{[-tb|-topbottom]}} {{path/to/input.pam}} > {{path/to/output.pam}}`

- Flip the input image on the main diagonal:

`pamflip {{[-xy|-transpose]}} {{path/to/input.pam}} > {{path/to/output.pam}}`
