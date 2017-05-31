# JSON Feed for Hugo

A simple feed file that follows the [1.0 spec](https://jsonfeed.org/version/1) of the JSON Feed standard established by [Manton Reece](http://manton.org/) and [Brent Simmons](http://inessential.com/).

## Installation
Copy the `index.json` file to the root layout folder of your Hugo site.

Add the following lines to your `config.toml` file.

```
[outputs]
home = ["HTML", "RSS", "JSON"]
```