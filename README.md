# tfl: London Transport status in your terminal.

[![License: BSD 3 Clause](https://img.shields.io/badge/License-BSD_3--Clause-yellow.svg)](https://opensource.org/licenses/BSD-3-Clause)

A little `bash` script to show the current status of London transport, as reported by [TFL](https://tfl.gov.uk/).
Useful for those who live in London, UK, because the dynamic nature of London transport is probably worth
a dedicated Linux command.

#### Example output (at a typical weekend):
```bash
$ tfl
Bakerloo            Good service
Central             Good service
Circle              Good service
District            Part closure
DLR                 Part closure
Hammersmith & City  Part closure
Jubilee             Good service
London Overground   Reduced service
Metropolitan        Good service
Northern            Good service
Piccadilly          Good service
TfL Rail            Good service
Tram                Part closure
Victoria            Good service
Waterloo & City     Good service

Source: https://tfl.gov.uk/tube-dlr-overground/status/
```

### Installation
Just copy the `tfl` file to a directory from your `$PATH` environment variable.

#### Dependencies:
```bash
sudo apt install html-xml-utils
```

### Status
The script has been tested on Linux Mint 19.1, and it will probably work on other
Ubuntu-based distributions as well.
Since the script is based on some naïve web-scraping it may break at any time.
