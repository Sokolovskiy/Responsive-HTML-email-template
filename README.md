# Responsive HTML Email Template


**Best Practices: Development**

Much like with design, there are best practices to follow when coding HTML email.

- Code all structure using the table element. For more complicated layouts, you should nest tables to build complex structures.
- Use element attributes (such as cellpadding, valign, and width) to set table dimensions. This forces a box-model structure.
- Keep your CSS simple. Avoid compound style declarations (IE: “font:#000 12px Arial, Helvetica, sans-serif;”), shorthand code (IE: #000 instead of #000000), CSS layout properties (IE: slot, position, clear, visibility, etc.), complex selectors (IE: descendant, child or sibling selectors, and pseudo-elements)
- Inline all CSS before sending. (Mailchimp will do this for you automatically.)
- Use only absolute links for images, and host those images on a reliable server. (Mailchimp provides free image hosting.)
- Don’t bother with JavaScript or Flash—those technologies are largely unsupported by email clients.
- Account for mobile-friendliness, if possible. Use media queries to increase text sizes on small screens, provide thumb-sized (~46x46px) hit areas for links. Make an email responsive if the design allows for it.
- Test, test, test. Create email accounts across various services, and send emails to yourself. Do this in conjunction with services such as Litmus.
