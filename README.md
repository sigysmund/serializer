# Serializer
[![Build Status](https://travis-ci.org/jms-serializer/serializer.svg?branch=master)](https://travis-ci.org/jms-serializer/serializer)

Learn more about it in its [documentation](http://jmsyst.com/libs/serializer).

## Overriding `jms/serializer`
I'd like to merge everything back into the original repository. That's why I haven't set a new name in the `composer.json`.

To install this fork of `jms/serializer`, you've to override the original repository. To do that, append this to your `composer.json`:

```json
    "repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/jms-serializer/serializer"
        }
    ]
```

## Notice for @schmittjoh
I hate to fork the library instead of getting the original up to speed.

In a perfect world, I'd like to move the original repository to an organization, add a few contributors and work through all of the issues / PR's.

It mustn't be that the most popular serializing library for PHP is unmaintained.
