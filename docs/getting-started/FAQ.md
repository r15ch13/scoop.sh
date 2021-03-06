*Do you have a question that's not answered here? Please create an issue.*

### How do I update my apps?

First, update Scoop to get the latest manifests:

```
scoop update
```

Then update the app, e.g. Git:

```
scoop update git
```

If you want to update all your apps at once, you can use the wildcard '*':

```
scoop update *
```

### How do I uninstall an app?

Use `scoop uninstall [app]`. E.g. for Git:

```
scoop uninstall git
```

### Scoop is very slow when installing, locks up the CPU, or shows access denied errors

It's likely that your antivirus or anti-malware program is doing a realtime scan as files are being extracted. Please see [Antivirus and Anti-Malware Problems](https://github.com/lukesampson/scoop/wiki/Antivirus-and-Anti-Malware-Problems) for more information and possible workarounds.

*[todo: insert more FAQS here]*