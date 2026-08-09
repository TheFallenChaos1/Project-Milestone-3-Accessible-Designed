Issue 1: Skipped Heading Level

WAVE saw a skipped heading level because the logo used the heading tag of “My Portfolio” which was an &lt;h2&gt; whereas the main heading on the page was an &lt;h1&gt;.

When using screen readers, users rely on heading tags to navigate a webpage. If heading levels are skipped, it can be confusing for those screen reader users to navigate the webpage.

Issue 2: Missing Form Labels

WAVE detected that the contact form on the Contact page was missing form labels for each of the form fields.

If a screen reader user does not know what information is required for each form field, they may have difficulty submitting the form correctly.

Issue 3: Low Contrast Text

Some of the text on the page has a muted or gray color which contrasts poorly against the dark background to which WAVE has alerted me.

Why it matters: This contrast makes it hard for individuals with low vision or color blindness to read the text on the page.

Reflection

Beyond the visual look of a website, accessibility pertains to the experience of individuals utilizing assistive technologies to navigate a website. WAVE has alerted me to an issue with my heading levels; the logo was marked as an <h2> but the page contained an <h1>. I changed the logo to a paragraph element to fix this issue.

WAVE also highlighted another accessibility issue regarding the contact form fields. These fields did not have labels, which makes it challenging for screen reader software to understand their purpose. By adding labels to each field and wrapping the fields in a fieldset, I have made the form field accessible.

Although these issues may seem small within the code for a website, they can have a great impact on the visitors of that site. Accessibility should be considered when building a website. Tools like WAVE can help developers to recognize accessibility issues prior to publishing a website and making it live for the public.
