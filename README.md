This is intended for Linux users coming from Windows who use a US International keyboard layout and need to write in Spanish more easily.

# Forked version

This is a **fork** of the original repo at https://github.com/raelgc/win_us_intl/

I have only edited the .XCompose file by ensuring that only Spanish combinations are available. Meaning: `Á É Í Ó Ú Ñ Ü á é í ó ú ñ ü`.

Moreover, I only use it with ibus (Alternative 2 in their repo), and therefore do not provide any other alternative methods.



# ibus

Modern versions of `ibus` appears to properly handle the `.XCompose` file.

So, download the file and place it at your home folder (and logout/login) should be enough to get proper latin accents:

    cd ~
    wget https://raw.githubusercontent.com/Squaredude/win_us_intl/master/.XCompose

Logout and login again.
