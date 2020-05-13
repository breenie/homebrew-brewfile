# homebrew-brewfile

Base Brewfile for setting up laptops

## Catalina ql notes

To get ql plugins working in Catalina, you will need to remove the quarantine attribute.

Run this to see the attributes:

```
xattr -r ~/Library/QuickLook
```

And run this to remove the attributes:

```
xattr -d -r com.apple.quarantine ~/Library/QuickLook
```
