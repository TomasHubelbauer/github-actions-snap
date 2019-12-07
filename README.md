# GitHub Actions Snap

## To-Do

### Figure out how to use Snap-installed software in GitHub Actions

GitHub Actions Ubuntu agents run passwordless sudo, but Snap-installed
software when invoked throws an error which says "not root owned".

Maybe it needs to be started with `sudo` or  some switch needs to be
passed or something.

Software where this was a problem: Blender, OpenSCAD (I think).
