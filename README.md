# WordPress Go-Live Checklist

This checklist serves as a systematic pre-launch verification tool for WordPress websites. While it assumes familiarity with WordPress implementation, each item includes key considerations and common pitfalls to watch for.

## Basic URL and Access Verification

- [ ] Site accessible at intended URL
  - [ ] Verify both www and non-www versions redirect properly
  - [ ] Check HTTPS implementation and certificate validity
  - [ ] Confirm no mixed content warnings
  - [ ] Test mobile and desktop accessibility

## WordPress Core Settings

- [ ] Site Identity Configuration
  - [ ] Site title matches brand guidelines
  - [ ] Tagline provides clear value proposition
  - [ ] Administrator email uses monitored address
  - [ ] Check email deliverability to prevent notifications going to spam

- [ ] URL Structure
  - [ ] Permalinks follow SEO best practices (typically /post-name/)
  - [ ] Custom post types have logical URL patterns (e.g. /projects/mars-landing/)
  - [ ] No duplicate content issues from multiple URL paths
  - [ ] 404 page exists and provides helpful navigation

- [ ] Visual Identity
  - [ ] Logo displays correctly across all breakpoints
  - [ ] Favicon appears in all major browsers
  - [ ] Touch icons set for mobile devices
  - [ ] Brand colors consistent throughout interface

## Essential Functionality

- [ ] Email System
  - [ ] WordPress can send system emails
  - [ ] Contact forms deliver to correct recipients
  - [ ] Email formatting is professional
  - [ ] SPF and DKIM records configured if using custom domain

- [ ] Content Management
  - [ ] Comments policy implemented (moderation or disabled)
  - [ ] Time zone matches business location
  - [ ] Date format appropriate for target audience
  - [ ] Media library organized with proper file names
  - [ ] Internal links validated and functional

## WordPress Optimization

- [ ] Content Display
  - [ ] Posts page configuration matches requirements
  - [ ] Archive pages show correct content
  - [ ] Category and tag pages properly formatted
  - [ ] Search functionality works as expected

- [ ] User Experience
  - [ ] Navigation menus are intuitive
  - [ ] Mobile responsiveness verified
  - [ ] Forms have proper validation
  - [ ] Error messages are user-friendly

## E-commerce Considerations

- [ ] Product Management
  - [ ] Product pages display all necessary information
  - [ ] Product images optimize for performance and quality
  - [ ] Inventory management configured
  - [ ] Product categories and filters work properly

- [ ] Purchase Process
  - [ ] Checkout flow tested with multiple scenarios
  - [ ] Payment gateways properly configured
  - [ ] Order confirmation emails work
  - [ ] Tax calculations accurate
  - [ ] Shipping options make sense

## SEO Implementation

- [ ] Technical SEO
  - [ ] XML sitemap generated and accessible
  - [ ] Robots.txt properly configured
  - [ ] No indexation blocks on important pages
  - [ ] Schema markup validates in testing tools

- [ ] Content SEO
  - [ ] Meta descriptions present on key pages
  - [ ] Title tags follow best practices
  - [ ] Image alt text implemented
  - [ ] Heading hierarchy logical and complete
  - [ ] Taxonomies have proper meta information

## Security Measures

- [ ] Access Control
  - [ ] Admin username changed from default (e.g. 'greg', not 'admin')
  - [ ] Strong password policy enforced
  - [ ] User roles properly assigned
  - [ ] Development accounts removed
  - [ ] Failed login protection active

- [ ] System Security
  - [ ] WordPress core up to date
  - [ ] Plugins and themes updated
  - [ ] Admin login URL obscured (optional)
  - [ ] XML-RPC properly secured
  - [ ] Debug mode disabled in production

## Performance Optimization

- [ ] Basic Optimization
  - [ ] Asset minification implemented
  - [ ] Image optimization active
  - [ ] Caching solution configured
  - [ ] Database optimized
  - [ ] GTmetrix scores acceptable

- [ ] Advanced Performance
  - [ ] CDN properly configured
  - [ ] Browser caching implemented
  - [ ] GZIP/Brotli compression active
  - [ ] Lazy loading for images
  - [ ] Critical CSS implemented

## Legal Compliance

- [ ] Required Pages
  - [ ] Privacy policy comprehensive and accessible
  - [ ] Terms of service clearly presented
  - [ ] Cookie policy implemented if needed
  - [ ] Imprint page for applicable jurisdictions

- [ ] Data Protection
  - [ ] GDPR compliance verified if applicable
  - [ ] Cookie consent system working
  - [ ] Data collection disclosed
  - [ ] Clear opt-out mechanisms

## Third-Party Integration

- [ ] Analytics and Tracking
  - [ ] Analytics tracker properly installed
  - [ ] Goals and events configured
  - [ ] Google Search Console verified
  - [ ] Conversion tracking active

- [ ] Social Integration
  - [ ] Social share buttons functional
  - [ ] Social profile links accurate
  - [ ] Open Graph tags implemented
  - [ ] Twitter cards configured

## Maintenance Planning

- [ ] Backup Systems
  - [ ] Automated backup schedule established
  - [ ] Multiple backup locations used
  - [ ] Backup restoration tested
  - [ ] Critical files identified

- [ ] Monitoring
  - [ ] Uptime monitoring active
  - [ ] Performance monitoring configured
  - [ ] Security scanning scheduled
  - [ ] Error logging enabled

## Final Verification

- [ ] Cross-browser Testing
  - [ ] Site functions in all major browsers
  - [ ] Mobile experience verified
  - [ ] Forms tested across devices
  - [ ] Print styling checked

- [ ] Content Review
  - [ ] Placeholder content removed
  - [ ] Contact information accurate
  - [ ] Legal text approved
  - [ ] Grammar and spelling checked
