## smfCurve2 - Curve Skin for MediaWiki

This is Mediawiki Skin based on Curve for SMF development repository.
This theme is licensed under [BSD 3-clause license](http://www.opensource.org/licenses/BSD-3-Clause)

######Branches organization:
* ***master*** - is the main branch, supporting MediaWiki 1.31 (LTS)
* ***1.0*** - Initial Version

###### Notes:

Feel free to fork this repository and make your desired changes.

Please see the [Developer's Certificate of Origin](https://github.com/SimpleMachines/smfcurve2/blob/master/DCO.txt) in the repository:
by signing off your contributions, you acknowledge that you can and do license your submissions under the license of the project.

###### Branches organization:
* ***master*** - is the main branch
* ***1.0*** - Initial Version

###### Important Note for v1.0
This version is valid for MediaWiki 1.31 and later releases.
To install this skin;
* Download version 1.31+
* Unzip the file rename to smfcurve2
* Copy it into skins folder
* Open your LocalSettings.php file and add the following line to the end of the file

> wfLoadSkin( 'smfcurve2' );

* Find **$wgDefaultSkin** and set it to smfcurve2 as such

> $wgDefaultSkin = "smfcurve2";

###### How to contribute:
* fork the repository. If you are not used to Github, please check out [fork a repository](http://help.github.com/fork-a-repo).
* branch your repository, to commit the desired changes.
* sign-off your commits, to acknowledge your submission under the license of the project.
* an easy way to do so, is to define an alias for the git commit command, which includes -s switch (reference: [How to create Git aliases](http://githacks.com/post/1168909216/how-to-create-git-aliases))
* send a pull request to us.

Finally, feel free to play around. That's what we're doing. ;)