# Pranic Yoga Studio website refresh

## Reuse from the original files

| Source | Reused | Revised or removed |
| --- | --- | --- |
| html code_pranic.docx | HTML language and viewport metadata; stylesheet link; header and anchor navigation; hero, about, classes, schedule, contact, and footer sections; class-card structure | Actual browser-ready index.html; one page heading; semantic main/article elements; four current offerings; instructor bio; inquiry-based schedule; working telephone link |
| css style_pranic.docx | Cream #f5efe6, sage #a8c0a2, centered 1100px container, class-card grid, rounded cards, section spacing, footer concept | Flex navigation replaces floats; darker text improves readability; mobile layout and focus styles added; remote beach background and unloaded Open Sans font removed |
| README.md | Accessible East Bay yoga mission, Patanjali principles, scientific background, in-person/online/hybrid concept | Removes “kids’ yoga classes coming soon”; describes all four offerings and real website files |
| CNAME | pranicyogastudio.com | Preserved exactly |

Original DOCX files remain unchanged as reference material.

## Exact public copy

The complete proposed public copy is in index.html. The principal replacements are:

| Section | Original | Replacement |
| --- | --- | --- |
| Hero heading | Balance your body, mind & spirit | Calm the mind. Nourish the body. Awaken the breath. |
| Hero introduction | Welcome to Pranic Yoga Studio | Small-group yoga for adults, women, and children. Explore mindful movement, breathwork, and relaxation in a welcoming space. |
| Offerings | Beginner Yoga; Pranayama & Meditation; Gentle Flow; Restorative Yoga | Adult Hybrid Yoga; Kids’ Weekly Yoga; Kids’ Yoga Camps; Women’s Wellness Yoga |
| About | Generic studio description and evidence-based/transformative claims | Prachi Rajmane’s YTT-200 credential, PhD in Molecular Biology & Immunology, over nine years of personal practice, and teaching approach |
| Schedule | Monday Gentle Flow 6–7 PM; Wednesday Pranayama & Meditation 5:30–6:30 PM; Saturday Restorative Yoga 10–11 AM | Contact Prachi for the current timetable, class packages, rates, age groups, and available spaces. Please confirm your session and enrollment before attending. |
| Contact | Form without a delivery endpoint; info@pranicyogastudio.com; (123) 456-7890 | Call or text Prachi; clickable telephone link to (713) 449-5503; program/preferred-time inquiry guidance |

### Adult Hybrid Yoga

Build strength, flexibility, and balance through guided asanas, mindful movement, pranayama, and relaxation. Beginners are welcome, with options to adapt the practice to your comfort level.

### Kids’ Weekly Yoga

A playful introduction to yoga through movement, breathing, games, journaling, and quiet reflection. Children explore focus, confidence, and kindness while learning age-appropriate yoga concepts.

### Kids’ Yoga Camps

Explore yoga through asanas, breathwork, creative activities, journaling, games, and stories inspired by the yamas and niyamas. Contact Prachi for the next camp dates and age group.

### Women’s Wellness Yoga

A supportive practice for women, including women 40+, with gentle movement, strength and balance work, breath awareness, and relaxation. Make space for self-care through changing stages of life.

## Content decisions

- Offerings follow the owner’s current request and previously supplied program descriptions.
- Credentials and practice history follow the owner’s October 2, 2026 introduction.
- The telephone number was explicitly supplied as a public contact in a February 22, 2026 class announcement.
- The DOCX email and phone were placeholders, so the email is removed and the phone replaced.
- Prior schedules, prices, age ranges, and camp dates varied; the page uses contact-based enrollment until current details are confirmed.
- An earlier enrollment form URL exists, but its current program suitability and response acceptance are unverified; it is not used as a registration destination.
- Women’s programs are described as wellness practice without claims to treat conditions or regulate hormones.
- No booking backend, payment collection, or form delivery is introduced.

## Deployment and verification

This change adds static HTML/CSS at the repository root. It preserves CNAME and both DOCX files. Merge the proposed branch to the configured Pages source branch to make the code eligible for publication; actual publication depends on existing GitHub Pages settings and domain DNS.

Structural checks cover HTML parsing, unique IDs, internal anchor destinations, stylesheet existence, four offering cards, and removal of placeholder contact details and obsolete schedule copy. No browser render or live-domain publication is verified by those checks.
