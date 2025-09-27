# ISSUE: No Proper SEO Keywords - agathos.be Invisible in Search

## Problem Description
**Issue:** agathos.be is completely invisible in search results because it lacks proper SEO keywords and shows an error page instead of content.

**Current SEO Score:** 53/100 ❌  
**Main Problem:** No keywords people actually search for  
**Priority:** CRITICAL - Website cannot be found in search engines

## Why agathos.be Can't Be Found

### 1. **Error Page Instead of Content** - CRITICAL
- Website shows "An error has occurred :-(" 
- Search engines can't index error pages
- Zero SEO value
- **Impact:** Complete invisibility in search results

### 2. **No Target Keywords** - MAIN ISSUE
- Title: "Agathos - Rallying Christians to Serve the Communities Around Us"
- No keywords people actually search for
- Missing: "ministry management", "donor tools", "volunteer engagement"
- **Impact:** No search visibility

### 3. **Meta Description Too Long** - 188 characters
- Should be max 160 characters
- Gets cut off in search results
- **Current:** "Agathos empowers ministries and missions with tools and services for donor and volunteer engagement, event and project management — mobilising believers to serve the least, last, and lost."

## SEO Analysis Results (Rank Math)

### Failed Tests (9/27):
- ❌ No keywords in title & description
- ❌ No internal links (0 internal, 4 external)
- ❌ No canonical tag
- ❌ No Schema.org data
- ❌ WWW canonicalization issues
- ❌ Unminified CSS & JavaScript
- ❌ Slow response time (1.13s vs 0.8s target)
- ❌ Error page content
- ❌ No proper heading structure

### Warnings (7/27):
- ⚠️ Meta description too long
- ⚠️ No images with alt attributes
- ⚠️ Limited content depth
- ⚠️ No breadcrumb navigation
- ⚠️ Missing social media tags
- ⚠️ No FAQ schema
- ⚠️ Limited mobile optimization

## Target Keywords Missing

**What people actually search for:**
- "ministry management software"
- "donor management tools"
- "volunteer engagement platform"
- "church management system"
- "Christian ministry tools"
- "event management for churches"
- "Christian donation platform"
- "church event tickets online"

**Current title has none of these keywords!**

## Quick Fixes Needed

### 1. Fix Error Page (PRIORITY #1)
```bash
npm install
npm run webapp:build
./mvnw spring-boot:run
```

### 2. Add Proper Keywords
**New Title:**
```html
<title>Ministry Management Software | Donor Tools | Agathos - Christian Ministry Platform</title>
```

**New Meta Description:**
```html
<meta name="description" content="Agathos ministry management software helps churches manage donors, volunteers, and events. Free Christian ministry tools for engagement and outreach.">
```

### 3. Add Schema Markup
```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "SoftwareApplication",
  "name": "Agathos Ministry Management",
  "description": "Christian ministry management software for donor and volunteer engagement",
  "applicationCategory": "BusinessApplication",
  "operatingSystem": "Web Browser",
  "url": "https://agathos.be"
}
</script>
```

## Expected Results After Fix

- **SEO Score:** 53/100 → 80+/100
- **Search Visibility:** 0% → 60%+
- **Keywords Ranking:** Top 3 for target keywords
- **Organic Traffic:** 200%+ increase

## WordPress Solution Strategy

### Architecture Approach:
```
landing.agathos.be (WordPress Landing Page - SEO Optimized)
├── / (Homepage with clear CTAs)
├── /donate (Donation info → leads to main app)
├── /events (Event info → leads to main app)
├── /about (About Agathos)
└── /contact (Contact forms)

agathos.be (Main Web App - JHipster)
├── / (User-friendly landing with clear actions)
├── /donate (Actual donation process)
├── /events (Event ticket purchase)
├── /admin (Ministry Management)
├── /dashboard (User Dashboard)
└── /api (Backend Services)
```

### User Flow Strategy:
1. **SEO Discovery:** User finds agathos.be via search
2. **Landing Page:** WordPress page explains what Agathos does
3. **Call-to-Action:** "Start Donating" or "Buy Event Tickets"
4. **Main App:** User goes to agathos.be for actual transactions
5. **Clear Interface:** Modified index page shows exactly what to do

### WordPress SEO Benefits:
- ✅ **Free SEO Plugins:** Yoast SEO, RankMath, All in One SEO
- ✅ **Automatic SEO:** Meta tags, sitemaps, Schema markup
- ✅ **Easy Content Management:** Non-technical users can update
- ✅ **Mobile Optimization:** Responsive themes
- ✅ **Page Speed:** Caching plugins available
- ✅ **Search Engine Friendly:** Built-in SEO features

### WordPress SEO Plugins to Use:

#### 1. **Yoast SEO (Free)**
- Meta title and description optimization
- Keyword analysis
- Readability checks
- XML sitemap generation
- Schema markup

#### 2. **RankMath (Free)**
- Advanced SEO analysis
- Keyword tracking
- Local SEO features
- WooCommerce integration
- Performance monitoring

#### 3. **All in One SEO (Free)**
- Comprehensive SEO toolkit
- Social media optimization
- WooCommerce SEO
- Image SEO
- Advanced XML sitemaps

### WordPress Theme Recommendations:

#### 1. **Astra (Free)**
- Lightweight and fast
- SEO optimized
- WooCommerce ready
- Customizable headers/footers

#### 2. **GeneratePress (Free)**
- Performance focused
- SEO friendly
- Accessibility compliant
- Translation ready

#### 3. **OceanWP (Free)**
- WooCommerce optimized
- SEO ready
- Multiple demos
- Fast loading

### Expected Results:
- **SEO Score:** 53/100 → 85+/100
- **Search Visibility:** 0% → 70%+
- **Keywords Ranking:** Top 3 for target keywords
- **Organic Traffic:** 300%+ increase
- **Page Speed:** Under 3 seconds
- **Mobile Score:** 95%+

---

**Priority:** CRITICAL  
**Effort:** 2-4 hours for basic fixes  
**Impact:** High - Will make agathos.be findable in search results

**Note:** For user experience improvements and instant support, see separate issue: `support-ai-agent-instant-reply`
