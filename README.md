This project is for our homepage, https://whonix.org

# Development Goals

## No Third Party Resources

- Not fetching anything other than from whonix.org.

## Compatibility

ordered roughly by priority:
- Tor Browser
- Tor Browser with security slider set to maximum
- Chromium
- Firefox
- mobile Chromium
- mobile Firefox
- other browsers

## passing html5 W3C Markup Validation
https://validator.w3.org

# Misc
* Image conversion, resize and optimization is left to `ngx_pagespeed`.
* Not using relative links.
  * Using hardcoded, direct, full links to whonix.org images.
  * `ngx_pagespeed` filter `trim_urls` will convert them to relative links on the server on the fly.

# Links

## Standard

* https://www.whonix.org
* https://www.whonix.org/home.css

## Debugging

* https://www.whonix.org?PageSpeedFilters=+debug
* https://www.whonix.org?PageSpeed=off

## Caching Issues?

* https://www.whonix.org?PageSpeed=off
* https://www.whonix.org/home.css?PageSpeed=off

