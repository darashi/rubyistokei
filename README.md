# Rubyistokei

Introduce your Ruby heroes with the clock!

[![Build Status](https://travis-ci.org/darashi/rubyistokei.png)](https://travis-ci.org/darashi/rubyistokei)

## What is this?

Rubyistokei is a web application to show a clock of Rubyists, by Rubyists, for Rubyists. You can introduce your Ruby heroes to the world with the clock. "Tokei" (時計) means "clock" in Japanese.

Rubyistokei shows Rubyists every minute. We want to help Rubyists to know Rubyists each other by sight. Rubyistokei will be displayed during [RubyKaigi 2013](http://rubykaigi.org/2013 "RubyKaigi 2013, May 30 - Jun 1") in the venue.

So, we kindly ask you to add your Ruby heroes to this project. Instruction follows.

## How to add a Ruby hero?

1. Obtain permissions from both of the Rubyist and the photographer (if you are not of them).
2. Create metadata for the Rubyist under [data directory](https://github.com/darashi/rubyistokei/tree/master/data).
3. Send pull request.

## Hits

* The image is once scaled to be the long side of the image to 1024px, rendered the clock and bio, then rescaled to fit with the screen size.
* You need to restart server to reload database. [Shotgun](https://github.com/rtomayko/shotgun) may help you.
* You can fix the hero by specifying id in url hash. `http://localhost:9292/#person` will always show the person having id `person`. Useful for creating data.

## Any problem?

Please open [an issue](https://github.com/darashi/rubyistokei/issues).
