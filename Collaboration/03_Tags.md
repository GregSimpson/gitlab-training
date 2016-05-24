!SLIDE smbullets
# Git Tags

* Tag specific points in history
* Add, list, delete
* Push tags to remote repository
* Checkout branches based on tags

~~~SECTION:handouts~~~

****

Example for checking out a tag into a new branch:

    @@@ Sh
    $ git checkout -b version01 v0.1
    $ git branch

~~~ENDSECTION~~~


!SLIDE smbullets
# Lab ~~~SECTION:MAJOR~~~.~~~SECTION:MINOR~~~: Add Git Tag

* Objective:
 * Add git tag
* Steps:
 * Use `git tag` and add the `v0.1` tag
 * Verify the added tag with `git tag -l`

~~~SECTION:handouts~~~

****

~~~ENDSECTION~~~

!SLIDE supplemental exercises
# Lab ~~~SECTION:MAJOR~~~.~~~SECTION:MINOR~~~: Add Git Tag

## Objective: Add git tag
****

* Add git tag

## Steps:

* Use `git tag` and add the `v0.1` tag
* Verify the added tag with `git tag -l`


!SLIDE supplemental solutions
# Lab ~~~SECTION:MAJOR~~~.~~~SECTION:MINOR~~~: Proposed Solution
****

## Add git tag

****

### Add tag

    @@@ Sh
    $ git log
    $ git tag -m "Release v0.1" v0.1

### Verify tag

    @@@ Sh
    $ git tag -l

