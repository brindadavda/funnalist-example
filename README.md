# Funnelish Interview Practice Lab

## New in this repo

- `guides/funnelish-visual-playbook.md`: a complete 10-task walkthrough for building and visualizing Funnelish interview exercises, including desktop/mobile image briefs and short demo video storyboards.
- `prompts/funnelish-codex-prompt.txt`: an expanded reusable prompt that tells an AI exactly how to generate the step-by-step Funnelish guidance, visuals, and 5–10 second demo concepts.

---

This repository gives you a practical, repeatable way to practice a Funnelish-style interview task.

## What you'll practice

- Building a simple funnel page from scratch.
- Fixing width and spacing issues quickly.
- Making the page mobile responsive.
- Reusing sections to save time.
- Thinking like a conversion-focused builder instead of just a designer.

---

## Part 1: Practical Walkthrough

### 1) Create a funnel page from scratch

**Goal:** Build a clean landing page that clearly moves a visitor toward a purchase.

#### Steps

1. Go to **Funnels → Create New Funnel**.
2. Choose **Blank Funnel**.
3. Add a new page and select **Landing Page**.

#### Build the hero section

- Add a **Section**.
- Add a **Row** with **1 column**.
- Add these elements in order:
  - **Heading**: `🔥 Transform Your Skin in 7 Days`
  - **Paragraph**: `Clinically proven formula for glowing skin`
  - **Image**: product shot
  - **Button**: `Buy Now`

#### Recommended styling

- Alignment: center everything.
- Section padding: **80px top / 80px bottom**.
- Heading: large, bold, easy to scan.
- Button color: high contrast, such as orange or red.

#### Interview signal

A strong hero section shows that you understand visual hierarchy, message clarity, and CTA placement.

---

### 2) Fix a full-width section

**Common issue:** The section looks boxed instead of stretching across the page.

#### Fix

- Click the **Section** and set:
  - Width: **100%**
  - **Stretch Section**: enabled
- Click the **Row** and remove any restrictive max width.
  - Example: change `1200px` to no max width if the design calls for full stretch.

#### Common mistake

Leaving the builder's default boxed layout on the row while expecting the section to stretch visually.

---

### 3) Make the layout mobile responsive

Switch to mobile view and adjust the essentials.

#### Mobile changes

- Reduce heading size, for example **48px → 28px**.
- Stack multi-column layouts into **1 column**.
- Set images to **100% width**.
- Hide decorative or non-essential elements if they push the CTA too far down.

#### Pro tip

Try to keep the main CTA visible early without requiring long scrolling.

---

### 4) Add and customize core elements

Use the four basics well:

- **Heading**
- **Paragraph**
- **Button**
- **Image**

#### Good defaults

- Heading font weight: bold.
- Line height: around **1.4**.
- Bottom spacing between elements: **10px to 20px**.
- Alignment: choose center or left and stay consistent inside the section.

---

### 5) Duplicate a section to move faster

#### Steps

1. Right-click the section.
2. Choose **Duplicate**.
3. Update:
   - text
   - image
   - CTA label or CTA context

#### Why this matters

Speed is part of the interview. Reusing a known-good structure is faster and safer than rebuilding layouts from scratch.

---

### 6) Build a product section

Create a simple two-column layout:

- **Left:** product image
- **Right:** product details

#### Product content example

- Product name: `Glow Serum`
- Price: `₹999`
- Button: `Buy Now`
- Urgency text: `⚡ Limited Offer`

#### Why it works

This section combines product clarity, pricing, and urgency in one scannable block.

---

### 7) Add basic custom HTML/CSS

Use a custom HTML block when you want to demonstrate basic front-end comfort.

```html
<button style="background:red;color:white;padding:15px 30px;border:none;border-radius:5px;">
  Buy Now
</button>
```

#### Interview signal

You are showing that you can go beyond drag-and-drop when needed.

---

### 8) Fix common layout problems fast

#### Typical problems and fixes

- **Too much empty space** → reduce margin or padding.
- **Elements are misaligned** → check row alignment and column settings.
- **Content feels too narrow** → verify width settings and max width constraints.

#### Best debugging habit

Inspect the structure in this order:

**Section → Row → Element**

That helps you find where the layout is actually being constrained.

---

### 9) Build a simple multi-step funnel

#### Page 1: Landing page

- Product promise
- Hero image
- CTA button

#### Page 2: Checkout page

- Order form
- Payment integration concept such as Stripe or Razorpay

#### Page 3: Thank-you page

- Confirmation message
- Optional upsell or next-step CTA

---

### 10) Use a speed-task strategy

If you only have **10 to 15 minutes**, build in this order:

1. Hero section
2. Product section
3. Repeated CTA
4. Mobile fixes

#### Rule of thumb

Do not overdesign. Prioritize conversion clarity, spacing, and responsiveness.

---

## Part 2: Core Interview Concepts

### Section vs Row vs Element

- **Section**: the full-width container.
- **Row**: the structure layer that defines columns.
- **Element**: the actual content, such as text, buttons, or images.

### Conversion optimization basics

- Use one clear CTA.
- Add urgency carefully.
- Add social proof if time allows.
- Keep the page simple and uncluttered.

---

## Part 3: Reusable Codex-Style Prompt

You can paste the prompt below into Codex or ChatGPT to simulate a realistic Funnelish task.

```text
Act as a Funnelish expert and UI builder.

Your task is to generate step-by-step instructions and layout structure for building a high-converting funnel page.

Requirements:

1. Create a landing page with:

   * Hero section (headline, subheadline, product image, CTA button)
   * Product section (image, name, price, buy button, urgency text)
   * Clean spacing and alignment

2. Ensure:

   * Full-width responsive layout
   * Mobile optimization (stacked layout, adjusted font sizes)
   * Conversion-focused design

3. Include:

   * Section → Row → Element breakdown
   * Recommended padding, font sizes, and colors
   * CTA placement strategy

4. Add:

   * One duplicated section variation
   * Basic custom HTML button example

5. Also explain:

   * Common mistakes beginners make
   * Quick fixes for layout issues
   * How to build this in under 15 minutes

Output format:

* Structured steps
* Clear hierarchy
* Practical tips for interview scenario

Keep it simple, actionable, and optimized for speed.
```

The same prompt is also available in `prompts/funnelish-codex-prompt.txt` for quick reuse.

---

## Part 4: 15-Minute Practice Drill

### Minute 0 to 3

- Create the funnel.
- Add the hero section.
- Write the headline, subheadline, and CTA.

### Minute 3 to 7

- Add product image and product details.
- Create a clean product section.

### Minute 7 to 10

- Duplicate a section for variation or supporting content.
- Tighten spacing.

### Minute 10 to 13

- Switch to mobile view.
- Fix font sizes, image width, and stacking.

### Minute 13 to 15

- Review the CTA placement.
- Remove clutter.
- Make sure the page feels purchase-focused.

---

## Part 5: Common Beginner Mistakes

- Overdesigning before the main CTA is in place.
- Forgetting to check mobile.
- Using inconsistent spacing across sections.
- Leaving boxed layout settings when trying to create a full-width design.
- Adding too many elements that compete with the purchase action.

---

## Part 6: Final Practice Advice

When practicing, do these every time:

- Time yourself.
- Explain your choices out loud as if an interviewer is watching.
- Check mobile before you consider the task done.
- Ask yourself: **Will this page make people click Buy?**
