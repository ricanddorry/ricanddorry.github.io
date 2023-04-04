# ricanddory.github.io

A repository of Ric and Dorry Bradley's favorite work and memories. This archive was initiated as part of the celebration of Ric's 100th birthday and Dorry's memorial service in spring, 2022.

The code is deployed via Github pages at [ricanddorry.club](https://ricanddorry.club), but the repo can also be cloned if one would like to archive and browse all the content (except external links).


## Credits:
* Gallery uses [thumbsup](https://github.com/thumbsup/thumbsup) and the associated [github-pages-gallery](https://github.com/gautamkrishnar/github-pages-gallery)
* Avalanche book uses [Turn.js](http://www.turnjs.com)


## Maintenance:

### Update galleries

1. Use [Val's implementation of github-pages-gallery](https://github.com/veirs/ric_gallery_test)
2. To trigger the Github action, create a new folder within the gallery directory of `ric_gallery_test` and name it such that the folder name will be a good gallery title (generated automatically). Alternatively, follow this [guidance for adding a new gallery](https://github.com/veirs/ric_gallery_test#adding-a-new-album-to-gallery).
3. Clone [Val's implementation of github-pages-gallery](https://github.com/veirs/ric_gallery_test) after the continuous integration re/generates updated gallery html, thumbnails, etc. and then do `git checkout gh-pages` to download the new content.
4. Manually copy the whole gh-pages clone into this repo, replacing the content of `media/galleries`
5. Bonus step: to archive a copy of the original full-resolution photos, create a new folder within /media/photos in this repo and add them to it.
6. Push the new content to this repo.


