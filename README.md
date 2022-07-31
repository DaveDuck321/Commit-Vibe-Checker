# Vibe-Checker commit hook

Very cute, very useful commit hook to enforce good commit messages.


## Enlightening a normie step-by-step:

```bash
 > git commit -m "chore: fix typo in some boring thing"

   ASCII is boring (／ˍ・、)
     🎯 try something fun instead
Commit vibe-check failed (ﾉД`)!
1> git commit -m "chore: 👨‍⚕️🩹 typo in some boring thing (´Д`)"

   Why so sad (๑´╹‸╹`๑)???
     🎯 More happy words pls
Commit vibe-check failed (ノ_ <。)!
1> git commit -m "Fix 👨‍⚕️🩹 oopsy in the exciting file (*＾წ＾*)"

   Sorry, got bored (ᴗ˳ᴗ), not enough excitement '_'
     🎯 SHOW SOME PASSION!!!!
Commit vibe-check failed (ノ_ <。)!
1> git commit -m "Fix 👨‍⚕️🩹 oopsy in the EXCITING file (*＾წ＾*)!!!"
Success!!!
 >
```

## How to install

Temporarily:
```bash
> cd /path/to/any/repo
> cp /path/to/vibe-checker/commit-msg .git/hooks/
```

Permanently (for newly created/ cloned repos):
```bash
> git config --global init.templatedir '~/.git-templates'
> mkdir -p ~/.git-templates/hooks
> cp /path/to/vibe-checker/commit-msg ~/.git-templates/hooks/
```

For development
```bash
> cd /path/to/vibe-checker/.git/hooks
> ln -s ../../commit-msg
```

## How to uninstall

## How to configure
No configuration is needed -- this is perfect out-the-box 😇.
