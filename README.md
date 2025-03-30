# OpenDAF

OpenDAF is a DAF format files creator for DAF PM repositories. It can be used
to make a repository that is compatible with package managers that are
compatible to run DAF.

## Using OpenDAF

When started, just click the + button to add a package. The first prompt is
the package name, and the second prompt is for the DEB file URL. Once all
desired packages are listed, click Export. It will generate TXT files ib the
DAF format to put in a repository. DO NOT RENAME OR CHANGE THESE FILES WHEN
UPLOADING TO THE REPOSITORY, as they will stop working when changed.

## Notes

DAF files are very fragile to mess with if you don't know how arrays work.
Please do not directly change them from the source if you do not know what
you are doing.
