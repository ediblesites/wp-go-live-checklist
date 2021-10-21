# WordPress Go-Live Checklist

The WP Go-Live Checklist is intended to work like a pre-flight checklist. It is assumed that you know how to implement its proposed items, so it is not an instruction manual. In time, we may add links from this document to more detailed instructions, but the list will always attempt to remain clean and functional.

## The obvious

- [ ] Site visible at its desired URL.

## WordPress basic settings 

- [ ] Site title set
- [ ] Site tagline set - theme settings will often allow control over whether to show or suppress this on the site, but either way, this might appear in site's title depending on the SEO plugin's settings.
- [ ] Administrator email set to whoever needs to receive important site notifications.
- [ ] Permalinks set correctly for posts and pages.
- [ ] Logo set, looks right on desktop, tablet, mobile.
- [ ] Favicon set

## Non-core, but still basic, site functionality
- [ ] Site can send (notification) emails. Test this by logging out and going through a 'forgot password' process.
- [ ] Commenting disabled, if applicable.
- [ ] Time zone set correctly.
- [ ] Date format set correctly.
- [ ] Permalinks set correctly for custom post types.
- [ ] Contact form works: sends submissions to right email address.
- [ ] No broken internal links.

## Wordpress behaviors to suppress



## Ecommerce

- [ ] Product pages look as expected.
- [ ] (Dummy) purchase works.

## SEO

- [ ] SEO plugin installed and configured
- [ ] Homepage and interior pages aren't blocked from crawling by 'noindex' tag. Check with...
- [ ] Tested for errors on Google schema tester - provide link
- [ ] Posts and pages have meta descriptions.
- [ ] Optionally: Categories and tags have meta descriptions.

## Security

- [ ] Admin username isn't 'admin'.
- [ ] Strong admin password set.
- [ ] No unnecessary users allowed (might be leftovers from development process).
- [ ] Non-admin users only have permissions as high as their job requires.
- [ ] Failed login mitigation.
- [ ] Optionally: admin login address moved.
- [ ] RPC-XML
- [ ] File debug.txt not publicly visible.

## Performance - basic

- [ ] CSS and JS minification
- [ ] Full-page caching installed and activated
- [ ] Tested on GTMetrix

## Performance - advanced

- [ ] CDN

## Compliance

Note: the following depend on the jurisdiction under which the site runs and its requirements

- [ ] Privacy page exists and is visibly linked.
- [ ] "Imprint" page exists and is visibly linked.
- [ ] If using optional cookies and/or data collection - GDPR notice.

## Third-party integrations

- [ ] Analytics installed and configured.
- [ ] Google Search Consoled defined.
- [ ] Social media links work.

## Avoiding regrets

- [ ] Site database and files are backed up periodically.
- [ ] External uptime service set up, configured, and working.
