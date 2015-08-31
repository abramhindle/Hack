## Frequently Asked Questions

### Install Issues

##### I am getting a "Does not appear to be a valid font" error message when I attempt to install on Windows 10.  How do I fix this?

Reported in https://github.com/chrissimpkins/Hack/issues/24

Turn your firewall on, then attempt to install the font again.


### Appearance Issues

##### The oblique style does not look correct in my JetBrains text editor (IntelliJ IDEA, WebStorm, PyCharm, etc) on OS X.  What is going on?

Reported in https://github.com/chrissimpkins/Hack/issues/26

This is a known issue with the Java renderer in these editors and not an issue with the font.  This has been reported on the JetBrains issue tracker.  Updates will be posted to the above issue report.

##### The there's a lot of space between characters when I use this font in emacs. What is going on?

Reported in https://github.com/chrissimpkins/Hack/issues/38

This seems to be a problem with the truetype fonts (.ttf files). Uninstall the ttf files and try installing the otf. Watch out for cached fonts or installing otf files for fonts that already exist as ttf. 

If you are on a Ubuntu or GNU/Linux system try removing the Hack font from your system. Check all directories checked by ```sudo fc-cache -f -v``` for Hack ttf and otf files. Remove those files. Then install only the otf files, not the ttf files.
