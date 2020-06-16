# CV

![Netlify](https://img.shields.io/netlify/0b5de811-e430-4d6d-876d-4bf3ee8c08be)

My personal CV, at <https://cv.jedevc.com>.

The single page on the site is generated from `data/resume.yaml`, whose
format was originally loosely inspired by [JSON Resume](https://jsonresume.org/),
but has since taken on a bit of a life of it's own.

## Development

Ensure [hugo](https://gohugo.io) is installed.

    $ git clone https://github.com/jedevc/cv.git
    $ cd cd

Run a live site preview:

    $ hugo server

Build the site:

    $ hugo

## License

This software is released under the UNLICENSE.

However, the contents of `data/resume.yaml` is personal information, and is
therefore withheld from the UNLICENSE.
