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
