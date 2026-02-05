# Claude Code Prompts — Hava Brhani Landing Page

## Before You Start

1. Create a new folder called `hava-landing`
2. Place **Hava's photo** in the folder as `hava.jpg` (or `hava.png`)
3. Open Claude Code in VS Code
4. Send each prompt **one at a time** — review the result before moving on

---

## Prompt 1 — Project Setup & Planning

```
Read the following skill files before starting:
- C:\Users\MoriaLevy\.claude\skills\agent-architect\SKILL.md
- C:\Users\MoriaLevy\.claude\skills\gsd-orchestration\SKILL.md

Then plan and set up a landing page project.

Project brief:
- Client: Hava Brhani (חוה ברהני), an Israeli Instagram content creator
- Goal: Landing page for her digital course "הצעד הראשון שלך להכנסה מהאינסטגרם" (Your First Step to Earning from Instagram)
- Target audience: Israeli mothers and women who want to start earning from Instagram
- Language: Hebrew, RTL direction
- Design style: Pastel pink + cream/ivory tones, feminine, warm, inviting
- Tech: Single index.html file (HTML + CSS + JS all in one file)
- Must be fully responsive (mobile-first)

Set up the project with:
- HTML boilerplate with RTL, lang="he"
- Google Fonts: Heebo (weights: 300,400,500,600,700,800,900)
- CSS variables:
  --pink-100: #FFF0F3
  --pink-200: #FFD6E0
  --pink-300: #FFB3C6
  --pink-400: #FF8FAB
  --pink-500: #E8678A
  --pink-600: #C94B6D
  --cream-50: #FFFDF8
  --cream-100: #FFF8EE
  --cream-200: #FFEFD6
  --text-dark: #3D2C2E
  --text-medium: #5A4447
  --text-light: #7D6366
- CSS reset and base styles
- No content yet — just the skeleton
```

---

## Prompt 2 — Hero Section

```
Add the Hero section to the landing page.

Structure (two columns on desktop, single column on mobile):

RIGHT COLUMN (content):
- Small badge: "✨ הקורס הדיגיטלי שישנה לך את הדרך"
- Main heading: "הצעד הראשון שלך להכנסה מהאינסטגרם"
  - The words "להכנסה מהאינסטגרם" should be in --pink-600 with a subtle highlight underline effect
- Paragraph: "היי! איזה כיף שאת כאן ואיזה כיף שבחרת לעשות משהו בשביל עצמך. את לא מאחרת. את בדיוק בזמן."
- CTA button (pink gradient, rounded): "רוצה להתחיל ←" linking to #payment

LEFT COLUMN (image):
- Hava's photo (hava.jpg from the project folder) in a frame with arch-shaped top (large border-radius on top, smaller on bottom)
- Two floating badges animating up/down: "💰 הכנסה מהבית" and "❤️ בקצב שלך"

Background: Subtle gradient from cream to pastel pink with a faint SVG dot/cross pattern overlay.
Decorative blurred color blobs (pink and cream) positioned behind the content.
Fade-in animation on page load.
```

---

## Prompt 3 — "Who Is This For" Section

```
Add a new section after the Hero — "Who is this course for?"

Background: white.

Content:
- Small tag label: "למי הקורס הזה מתאים?"
- Heading: "אם את קוראת את זה, כנראה שעברה לך לפחות פעם אחת המחשבה:"
- Large italic quote in pink: ״איך אני אמורה להתחיל עכשיו?״

Paragraphs:
1. "הרבה אמהות מרגישות שהן פספסו את הרכבת, שהן כבר אולי מבוגרות מדי בשביל להתחיל
שאם הן לא התחילו בגיל 20, או לא בנו עסק “מסודר”, אז זה כבר לא רלוונטי כרגע."


2. (with "אבל האמת היא הפוכה לגמרי." in bold): "אבל האמת היא הפוכה לגמרי. דווקא אמהות, דווקא נשים באמצע החיים הן אלה שהכי יודעות למה אין להן זמן, מה זה ממש רגעי ומה באמת יכול לעבוד."

Below — a grid of 3 cards (cream background, subtle border, hover lift effect):
1. 🙅‍♀️ | "את לא צריכה" | "להיות משפיענית עם עשרות אלפי עוקבים, לדעת לשווק או להעלות תוכן מושלם"
2. ✅ | "את כן צריכה" | "ניסיון חיים, מה שיש לך באופן טבעי מעצם היותך אישה ואמא, כוונות ורצון לעשות צעד אחד קטן בשבילך"
3. 📱 | "אינסטגרם היום מאפשר" | "להתחיל בקטן, בלי להפוך את זה לעסק גדול ובלי להקריב את הזמן היקר כ״כ חשוב עם הילדים שלנו אם את מרגישה הזדהות כשאת רואה אמא כמוך שמנסה – זה סימן חזק בשבילך שגם את יכולה.
"
```

---

## Prompt 4 — "Not Selling, Sharing" Section

```
Add a new section — "לא מוכרות, משתפות!"

Background: gradient from cream to light pink.

Heading: "לא מוכרות, משתפות!"

Opening text:
"הרבה נשים מפחדות מהשלב הזה. ״מה, פתאום למכור?״ ״זה לא ירגיש/ייראה מוזר?״"

Paragraph:
"האמת היא שאת לא מתחילה ממכירה, את מתחילה משיתוף. את לא מודיעה: ״יש לי מוצר, תקנו.״ את מספרת על משהו שפחדת ממנו, על איזשהו תהליך שעברת, תובנה שעשתה לך סדר בחיים, משהו שיגרום להזדהות איתו."

Example: "לדוגמה:"

3 styled quote blocks (white background, pink right border, chat-bubble feel, 💬 emoji decoration, hover slide effect):
1. "הרבה זמן רציתי לנסות להרוויח מהאינסטגרם אבל פחדתי..."
2. "הבנתי שאני לא צריכה עסק גדול, רק משהו אחד קטן שעובד לי"
3. "סידרתי לעצמי מסמך שעשה לי סדר בראש"

Then: "ואז, בטבעיות את רושמת:"

Closing paragraph (emphasized):
"אם זה יעזור אפילו לעוד אמא אחת אני עשיתי את שלי, שמה לכן לינק מסודר. אנשים לא קונים ממישהי שיודעת הכל. הם קונים ממי שצעדה צעד אחד לפניהם. את לא צריכה להיות מוכנה לגמרי, רק להיות אמיתית."
```

---

## Prompt 5 — "Choose a Small Problem" Section

```
Add a new section — "אנחנו לא בוחרים חלום. בוחרים בעיה אחת קטנה."

Background: white.

Heading: "אנחנו לא בוחרים חלום. בוחרים בעיה אחת קטנה."

Text:
"הטעות הכי גדולה בתחילת הדרך היא לחשוב: ״מה אני רוצה להיות?״ בלוגרית? יזמית? יוצרת תוכן? אבל כדי להתחיל - לא צריך זהות גדולה."

Highlighted block (pink-cream gradient background, centered, large text, rounded):
"צריך בעיה אחת קטנה שאפשר לפתור."

Sub-heading: "תשאלי את עצמך בכנות:"
List with decorative icons (not standard bullets):
• "על מה אנשים שואלים אותי שוב ושוב?"
• "במה אני עוזרת לחברות, לאחיות, לעוקבות?"
• "איזה דבר עברתי, הסתבכתי בו, ולמדתי ממנו?"

Text:
"הרעיון למוצר ראשון לא צריך להיות מרגש. הוא צריך להיות שימושי."

Examples block (light background):
"דוגמאות - מסמך פשוט שעושה סדר בלו״ז של אמא, רשימת רעיונות לתוכן לאינסטגרם, מדריך קצר להתחלה. את לא צריכה ליצור קורס, ליווי, או איזה משהו שלוקח חודשים להכין וגם עולה לנו הון. מספיק מסמך אחד שמרכז ידע, תובנות וניסיון חיים."

Exercise box (dashed border, cream background):
Title: "✏️ תרגיל קצר לעצמך:"
Text: "שבי עם עצמך ותכתבי לך עכשיו רעיון אחד בלבד. לא 3 ולא 5, רעיון אחד שעולה לך לראש שיכול לעזור לאחרים, זה יהיה הבסיס שלך."
```

---

## Prompt 6 — CTA / Payment Section

```
Add the CTA / payment section with id="payment".

Background: Light pink gradient with decorative elements.
Center-aligned text.

Heading: "בקיצור,"

Text:
"את לא מתחילה למכור, את מתחילה להאמין בעצמך שזה אפשרי ולהתחיל לעשות פעולות. וצעד ראשון אחד מספיק כדי לפתוח לך דרך חדשה."

Warm closing line (italic style):
"תנסי, מקסימום תצליחי ♡"

Price display (large, bold, pink-600):
"₪___" (placeholder — I'll fill in later)

Large pink CTA button with subtle pulse animation:
"!אני רוצה להתחיל עכשיו"
Link: "#" (placeholder — I'll replace with actual payment link later)

Three feature badges below the button in a row:
✓ גישה מיידית לקורס
✓ קבלה במייל
✓ תמיכה באינסטגרם

Small gray text at the bottom:
"לאחר התשלום תישלח אליך קבלה והקורס ישירות למייל"
```

---

## Prompt 7 — Footer with Social Links

```
Read the following skill file before starting:
- C:\Users\MoriaLevy\.claude\skills\svg-logo-designer\SKILL.md

Add a footer to the page.

Background: dark (#3D2C2E), text in cream tones.

Content:
- Name: "חוה ברהני"
- Social media icons in circles (use clean inline SVG icons) with real links:
  - Instagram: https://www.instagram.com/hava_brhani?igsh=cnZzZWVhZXJjOGxt
  - TikTok: https://www.tiktok.com/@havabrhani?_r=1&_t=ZS-93fbgaUc6a7
  - Facebook: https://facebook.com/hava.kasso
- All links open in new tab (target="_blank" rel="noopener")
- Hover effect: background turns pink
- Small copyright text: "© 2025 חוה ברהני. כל הזכויות שמורות."

Create clean, recognizable SVG icons for Instagram, TikTok, and Facebook. Don't use external icon libraries.
```

---

## Prompt 8 — Animations & Polish

```
Read the following skill file before starting:
- C:\Users\MoriaLevy\.claude\skills\visual-review-skill\SKILL.md

Add animations and polish to the entire page:

1. Scroll animations — every section fades in + slides up when entering the viewport (use IntersectionObserver, threshold 0.15)
2. Sticky mobile CTA — a fixed bottom button on mobile that hides when the payment section is visible
3. Decorative blurred blobs in the Hero background with subtle parallax on scroll
4. Hover effects on all cards (translateY + shadow increase)
5. Smooth scroll for all internal anchor links
6. Subtle SVG pattern texture overlay on the Hero section

Verify:
- No horizontal overflow at any screen size
- Animations use transform/opacity only (GPU-friendly, no layout thrashing)
- Works smoothly at 375px (mobile) and 1440px (desktop)
- RTL direction is correct everywhere

After implementing, use the visual-review-skill to review the page visually and fix any issues.
```

---

## Prompt 9 — SEO & Meta Tags

```
Add SEO and meta tags to the page:

1. Meta tags:
   - title: "הצעד הראשון שלך להכנסה מהאינסטגרם | חוה ברהני"
   - description: "קורס דיגיטלי לנשים ואמהות שרוצות להתחיל להרוויח מאינסטגרם. ללא ניסיון קודם, בקצב שלך, צעד אחד קטן שמשנה הכל."
   - Open Graph: og:title, og:description, og:image, og:type=website, og:locale=he_IL
   - Twitter card tags

2. Favicon — create an inline SVG favicon of a pink heart

3. Preload the Heebo font for better performance

4. Add descriptive Hebrew alt text to all images

5. Add JSON-LD structured data (type: Course) with:
   - name: "הצעד הראשון שלך להכנסה מהאינסטגרם"
   - provider: "חוה ברהני"
   - language: "he"
```

---

## Prompt 10 — Final QA Review

```
Read the following skill file:
- C:\Users\MoriaLevy\.claude\skills\visual-review-skill\SKILL.md

Do a full QA review of the landing page. Open the page and check:

1. No horizontal overflow at any screen width
2. Fonts load correctly (Heebo in all weights)
3. All links work (social media links, internal anchors)
4. RTL is correct everywhere — including quote borders on the RIGHT side, text alignment, floating elements
5. Looks great at: 375px, 768px, 1024px, 1440px
6. Color palette is consistent (pastel pink + cream, no stray colors)
7. Text contrast meets WCAG AA (especially light text on light backgrounds)
8. CTA buttons are prominent and accessible
9. Hava's photo loads correctly and is well-framed
10. Performance — no unnecessary resources, images optimized

Fix any issues you find. List what was fixed.
```

---

## Pre-Launch Checklist

- [ ] Replace `₪___` with actual course price (ask Hava)
- [ ] Replace `#` in payment button with actual payment link (GROW / bit)
- [ ] Verify Hava's photo (`hava.jpg`) loads and looks good
- [ ] Test on a real mobile device (not just DevTools)
- [ ] Test all social media links actually open correctly
- [ ] Purchase domain and deploy (Hava is handling domain separately)
- [ ] Set up post-payment email with receipt + course access
