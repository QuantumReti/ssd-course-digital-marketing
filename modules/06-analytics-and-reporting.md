# Module 06: Analytics and Reporting

## Why Measurement Is Non-Negotiable

Analytics serves two purposes:
1. Internal: Understanding what is working so we can do more of it and fix what is not
2. Client-facing: Demonstrating the value of our services in clear, plain English

Every client deserves to know their investment is working. Every team member needs to understand the numbers behind the results they are delivering.

---

## Google Analytics 4 (GA4)

GA4 is the current version of Google Analytics. Every client website should have GA4 installed from day one.

### Setting Up GA4
1. Go to analytics.google.com - Create Account - Create Property
2. Set up a Web data stream with the client's website URL
3. Add the GA4 tracking code (Google tag) to the website
4. Verify tracking is active using the Realtime report
5. Connect GA4 to Google Search Console (for combined data)
6. Set up conversion events (form submissions, phone click, booking confirmations)

### Reading the GA4 Dashboard: Key Metrics

Users vs Sessions:
- Users: unique individuals who visited the site
- Sessions: total visits (one user can have multiple sessions)

Engagement Rate:
GA4 replaced bounce rate with engagement rate. An engaged session lasted 10+ seconds, OR had a conversion event, OR had 2+ pageviews.
Target: 50%+ engagement rate

Average Engagement Time:
How long users actively engage with the site.
Target: 1:30+ minutes for service businesses

Traffic Sources (Acquisition Report):
Where visitors are coming from:
- Organic Search (Google/Bing - free search traffic)
- Direct (typed URL or no referral data)
- Referral (from another website)
- Paid Search (Google Ads)
- Organic Social (Facebook, Instagram)
- Email

Target for established SMB sites: 40%+ from organic search (indicates SEO is working)

---

## Google Search Console (GSC)

Search Console shows how Google sees and indexes your website. Essential for SEO monitoring.

### Key Metrics in GSC

Total Impressions: How many times your website appeared in Google search results.

Total Clicks: How many times someone clicked through to your website from Google.

Average Click-Through Rate (CTR): Clicks divided by Impressions.
Target CTR by position:
- Position 1-3: 10-30% CTR
- Position 4-7: 5-10% CTR
- Position 8-10: 2-5% CTR

Average Position: Average ranking across all keywords you appear for.
Target: Primary keywords in top 10 (first page)

### Key Reports to Check Monthly

Performance Report:
- Top queries: What searches bring people to your site?
- Are the target keywords in the top 10?
- Are there keywords ranking on page 2 (positions 11-20) that could be pushed to page 1?

Coverage Report:
- Any errors = pages Google cannot index. Must fix these promptly.

Core Web Vitals:
- LCP (Largest Contentful Paint): How fast the main content loads. Target: under 2.5 seconds
- INP (Interaction to Next Paint): How quickly the page responds. Target: under 200ms
- CLS (Cumulative Layout Shift): Does the page move around while loading? Target: under 0.1

---

## Conversion Tracking

What Counts as a Conversion for a Service Business:

Primary Conversions (highest value):
- Phone number click (on mobile)
- Contact form submission
- Online booking completion
- Quote request form submission

Secondary Conversions (lower value but informative):
- Click on email address
- Direction request click (from GBP to Maps)
- Services page visit (shows research intent)
- Time on site over 3 minutes (highly engaged visitor)

---

## Monthly Reporting Template

Every active client should receive a monthly report. Written in plain English - no jargon, no confusing acronyms.

### Report Structure

1. Executive Summary (2-3 sentences)
This month, your website received [X] visits from Google - up [Y]% from last month. We generated [Z] new leads through the contact form and phone click tracking. Your Google Business Profile appeared in [X,XXX] searches.

2. Website Traffic
| Metric | This Month | Last Month | Change |
|--------|-----------|-----------|--------|
| Total Users | | | |
| Organic Search Users | | | |
| Sessions | | | |
| Engagement Rate | | | |

3. Google Business Profile Performance
| Metric | This Month | Last Month |
|--------|-----------|-----------|
| Total Searches | | |
| Profile Views | | |
| Website Clicks | | |
| Phone Calls (GBP) | | |
| Direction Requests | | |

4. Conversions and Leads
| Source | Leads | Notes |
|--------|-------|-------|
| Website form | | |
| Phone clicks | | |
| GBP calls | | |
| Total | | |

5. SEO Rankings
Top keywords being tracked and their current positions.

6. What We Did This Month
List of work completed: blog posts published, GBP optimisation, new photos added, reviews received, etc.

7. Next Month Focus
What we are working on: new suburb pages, content plan, campaign changes, etc.

---

## Red Flags to Watch

### Bounce Rate Spike (or Engagement Rate Drop)
Possible causes: Site speed issue, irrelevant traffic source, broken page, content mismatch with ads.
Action: Check PageSpeed Insights, review traffic sources, test the page on mobile.

### Sudden Traffic Drop
Possible causes: Google algorithm update, manual penalty, tracking code removed, website error.
Action: Check Search Console for manual actions or errors, compare dates to known algorithm updates.

### Conversion Rate Drop
Possible causes: Form broken, phone number changed, landing page updated without testing, seasonal factors.
Action: Test all conversion paths immediately. Check for 404 errors on thank-you pages.

### Google Business Profile Views Drop
Possible causes: Category change, suspension risk, competitor gained more reviews, GBP listing issue.
Action: Check GBP dashboard for warnings, review recent changes, check review velocity.

---

## How to Explain Results to Clients in Plain English

Never say: Your organic CTR improved by 2.3% and your engagement rate increased to 54%.

Say instead: More people are finding your website on Google - 30% more than last month. And when they visit, they are staying longer and actually contacting you more. The phone click numbers are up, which means real people are seeing your number and calling.

The rule: Every metric needs a so what attached to it.

- Traffic is up 30% = 30% more potential customers found your business on Google
- Average position improved from 12 to 7 = You went from page 2 to the bottom of page 1 for your main keywords
- 15 phone clicks from the website = 15 people saw your number and clicked to call you
- 8 form submissions = 8 people filled in your contact form to request a quote

Make every number mean something to a business owner who does not know what GA4 is.

*Sun State Digital - Digital Marketing Mastery Course | Module 06*