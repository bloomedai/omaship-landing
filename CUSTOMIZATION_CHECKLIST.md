# 📋 Customization Checklist

This guide walks you through customizing every part of your landing page. Each item includes the exact location in `index.html` where you need to make changes.

## 🎯 Before You Start

1. Open `index.html` in your favorite code editor
2. Use Ctrl+F (or Cmd+F) to search for the `<!-- CUSTOMIZE: -->` comments
3. Work through this checklist in order for best results
4. Preview your changes by opening `index.html` in your browser

## 🏷 Essential Branding

### ✅ Page Title & Meta Tags
**Location**: `<head>` section (lines 6-34)

- [ ] **Page Title** - Replace "Your SaaS Landing Page - Ship Faster, Validate Smarter"
- [ ] **Meta Description** - Update the description for search engines
- [ ] **Keywords** - Add relevant keywords for your niche
- [ ] **Open Graph Title** - For social media sharing
- [ ] **Open Graph Description** - Description when shared on social
- [ ] **Open Graph Image** - Add your brand image URL
- [ ] **Twitter Card Tags** - Update for Twitter sharing

**Example**:
```html
<title>TaskFlow - The Ultimate Project Management Tool</title>
<meta name="description" content="Streamline your team's workflow with TaskFlow. Manage projects, track time, and boost productivity with our intuitive platform.">
```

### ✅ Brand Logo & Name
**Location**: Navbar section (line 67)

- [ ] **Logo Icon** - Replace `data-lucide="rocket"` with your preferred Lucide icon
- [ ] **Brand Name** - Replace "YourBrand" with your actual brand name
- [ ] **Logo Link** - Update href if needed

**Example**:
```html
<a class="btn btn-ghost text-xl" href="#hero">
    <i data-lucide="zap" class="h-6 w-6"></i>
    TaskFlow
</a>
```

### ✅ Favicon
**Location**: `<head>` section (line 35)

- [ ] **Favicon** - Replace `/favicon.svg` with your actual favicon path
- [ ] Create and upload your favicon file to the root directory

## 🎯 Hero Section

### ✅ Headlines & Copy
**Location**: Hero section (lines 103-133)

- [ ] **Main Headline** - Replace "Ship Your SaaS Idea in Minutes, Not Months"
- [ ] **Subheadline** - Update the value proposition description
- [ ] **Primary CTA Button** - Change "Start Building Now" text and link
- [ ] **Secondary CTA Button** - Update "See How It Works" text and link
- [ ] **Social Proof Line** - Replace the "Join 2,000+ entrepreneurs" text

**Example**:
```html
<h1 class="text-4xl md:text-6xl font-bold mb-6">
    Manage Projects Like a
    <span class="text-primary">Pro</span>
</h1>
<p class="text-lg md:text-xl mb-8 max-w-2xl mx-auto opacity-80">
    TaskFlow helps remote teams stay organized and productive. Track projects, manage deadlines, and collaborate seamlessly.
</p>
```

## 🌟 Features Section

### ✅ Section Header
**Location**: Features section (lines 141-149)

- [ ] **Section Title** - Update "Everything You Need to Launch"
- [ ] **Section Subtitle** - Replace with your product benefits

### ✅ Feature Cards (6 Total)
**Location**: Feature grid (lines 153-245)

For each feature card, update:
- [ ] **Icon** - Change the `data-lucide` icon name
- [ ] **Title** - Replace the feature title
- [ ] **Description** - Write your feature description

**Example Feature Card**:
```html
<div class="mx-auto w-12 h-12 bg-primary/20 rounded-lg flex items-center justify-center mb-4">
    <i data-lucide="users" class="h-6 w-6 text-primary"></i>
</div>
<h3 class="card-title justify-center">Team Collaboration</h3>
<p class="opacity-70">Work together seamlessly with real-time updates, comments, and file sharing.</p>
```

## 🔄 How It Works Section

### ✅ Process Steps
**Location**: How It Works section (lines 265-304)

- [ ] **Section Title** - Update "Launch in 3 Simple Steps"
- [ ] **Section Subtitle** - Replace with your process description
- [ ] **Step 1** - Title and description for first step
- [ ] **Step 2** - Title and description for second step  
- [ ] **Step 3** - Title and description for third step

**Example Step**:
```html
<h3 class="text-xl font-semibold mb-4">Sign Up & Invite Team</h3>
<p class="opacity-70">Create your workspace in 30 seconds. Invite your team members and start collaborating immediately.</p>
```

## 👥 About/Team Section

### ✅ Team Information
**Location**: About section (lines 318-355)

- [ ] **Section Title** - Update "Meet Your Team"
- [ ] **Team Photo** - Replace placeholder image URL
- [ ] **Name** - Replace "Your Name"
- [ ] **Bio** - Write your founder/team bio
- [ ] **Skill Badges** - Update with relevant skills/technologies

**Example**:
```html
<h3 class="text-2xl font-semibold mb-2">Sarah Johnson</h3>
<p class="text-lg opacity-70 mb-4">
    Former VP of Engineering at Google with 10 years building scalable platforms. 
    Passionate about helping teams work more efficiently.
</p>
<div class="flex flex-wrap gap-2 justify-center md:justify-start">
    <span class="badge badge-primary">Leadership</span>
    <span class="badge badge-primary">Product Strategy</span>
    <span class="badge badge-primary">Team Building</span>
</div>
```

## 💰 Pricing Section

### ✅ Pricing Plans (3 Tiers)
**Location**: Pricing section (lines 374-478)

- [ ] **Section Title** - Update "Simple, Honest Pricing"
- [ ] **Section Subtitle** - Replace with your pricing description

For each pricing tier:
- [ ] **Plan Name** - Starter, Pro, Enterprise
- [ ] **Price** - Update the price and billing period
- [ ] **Features List** - Replace with your actual features
- [ ] **CTA Button** - Update button text and link

**Example Pricing Card**:
```html
<h3 class="card-title text-2xl">Starter</h3>
<div class="text-3xl font-bold mb-4">
    $29
    <span class="text-lg font-normal opacity-70">/month</span>
</div>
<ul class="space-y-3 mb-8">
    <li class="flex items-center gap-2">
        <i data-lucide="check" class="h-4 w-4 text-success"></i>
        <span>Up to 5 team members</span>
    </li>
    <li class="flex items-center gap-2">
        <i data-lucide="check" class="h-4 w-4 text-success"></i>
        <span>10 projects</span>
    </li>
</ul>
```

## 💬 Testimonials Section

### ✅ Customer Reviews (3 Total)
**Location**: Testimonials section (lines 489-584)

For each testimonial:
- [ ] **Review Text** - Replace with real customer feedback
- [ ] **Customer Name** - Real customer name
- [ ] **Company/Title** - Customer's company and role
- [ ] **Avatar Image** - Customer photo (or use initials placeholder)

**Example Testimonial**:
```html
<p class="mb-4">"TaskFlow transformed how our remote team works together. We ship projects 40% faster now and everyone stays in sync."</p>
<div class="flex items-center gap-3">
    <div class="avatar">
        <div class="w-10 rounded-full">
            <img src="https://via.placeholder.com/40x40/10b981/ffffff?text=M" alt="Customer" />
        </div>
    </div>
    <div>
        <div class="font-semibold">Maria Garcia</div>
        <div class="text-sm opacity-70">CTO, StartupCo</div>
    </div>
</div>
```

## ❓ FAQ Section

### ✅ Questions & Answers (6 Total)
**Location**: FAQ section (lines 595-692)

- [ ] **Section Title** - Update if needed
- [ ] **Section Subtitle** - Replace with your FAQ description

For each FAQ:
- [ ] **Question** - Replace with real questions from customers
- [ ] **Answer** - Provide helpful, detailed answers

**Example FAQ**:
```html
<div class="collapse-title text-lg font-medium">
    How many team members can I add?
</div>
<div class="collapse-content"> 
    <p>The Starter plan includes up to 5 team members. Pro plan supports 25 members, and Enterprise has unlimited seats. You can upgrade anytime as your team grows.</p>
</div>
```

## 🎯 Final CTA Section

### ✅ Last Conversion Push
**Location**: Final CTA section (lines 703-723)

- [ ] **Final Headline** - Update "Ready to Ship Your Idea?"
- [ ] **Final Description** - Update conversion copy
- [ ] **CTA Button** - Update text and link
- [ ] **Guarantee Text** - Update guarantee/trust signals

## 📞 Footer

### ✅ Footer Links & Info
**Location**: Footer section (lines 726-765)

- [ ] **Footer Links** - Update navigation links
- [ ] **Social Media Links** - Add your actual social profiles
- [ ] **Contact Email** - Replace support email
- [ ] **Copyright** - Update company name and year
- [ ] **Legal Links** - Update privacy/terms links

**Example Social Links**:
```html
<a href="https://twitter.com/taskflowapp" class="link text-2xl hover:text-primary" aria-label="Twitter">
    <i data-lucide="twitter"></i>
</a>
```

## 🔗 CTA Button Links

### ✅ Update All Call-to-Action Links
Search for `href="#pricing"` and similar links throughout the file:

- [ ] **Primary CTAs** - Link to your signup/purchase page
- [ ] **Secondary CTAs** - Link to demos, trials, or contact forms
- [ ] **Pricing CTAs** - Link to your payment processor (Stripe, etc.)
- [ ] **Footer CTAs** - Update contact and legal page links

## 🎨 Advanced Customization

### ✅ Colors & Themes
- [ ] **Default Theme** - Change `data-theme="corporate"` in `<html>` tag
- [ ] **Custom Colors** - Modify Tailwind classes if needed
- [ ] **Brand Colors** - Consider using CSS custom properties for consistent branding

### ✅ Images & Media
- [ ] **Hero Background** - Consider adding a background image
- [ ] **Feature Icons** - Replace Lucide icons with custom SVGs if desired
- [ ] **Product Screenshots** - Add actual product images
- [ ] **Team Photos** - Use real team member photos

### ✅ Analytics & Tracking
- [ ] **Google Analytics** - Add tracking code to `<head>`
- [ ] **Facebook Pixel** - Add if using Facebook ads
- [ ] **Conversion Tracking** - Add event tracking to CTA buttons

### ✅ Forms & Integrations
- [ ] **Email Signup** - Connect to your email service (ConvertKit, Mailchimp, etc.)
- [ ] **Contact Forms** - Add form handling (Netlify Forms, Formspree, etc.)
- [ ] **Live Chat** - Add customer support widget
- [ ] **Payment Links** - Connect to Stripe, Gumroad, or your payment processor

## 🧪 Testing Checklist

### ✅ Before Going Live
- [ ] **Mobile Testing** - Test on phones and tablets
- [ ] **Browser Testing** - Check Chrome, Firefox, Safari
- [ ] **Link Testing** - Verify all links work correctly
- [ ] **Form Testing** - Test any contact/signup forms
- [ ] **Speed Testing** - Check page load speed
- [ ] **SEO Testing** - Verify meta tags and structure
- [ ] **Spelling/Grammar** - Proofread all content

### ✅ Post-Launch
- [ ] **Analytics Setup** - Verify tracking is working
- [ ] **Social Sharing** - Test how it looks when shared
- [ ] **Search Console** - Submit sitemap to Google
- [ ] **Performance Monitoring** - Set up uptime monitoring
- [ ] **A/B Testing** - Test different headlines/CTAs

## 🚀 Ready to Launch?

Once you've completed this checklist:

1. **Preview your changes** - Open `index.html` in multiple browsers
2. **Deploy to GitHub Pages** - Follow the deployment guide
3. **Set up analytics** - Add tracking codes
4. **Start promoting** - Share your new landing page!

Need help? Check out our [support resources](mailto:support@omaship.com) or join our [community Discord](https://discord.gg/omaship).

**Pro Tip**: Don't aim for perfection on day one. Launch with good content, then iterate based on real user feedback! 🎯