Q1: What are semantic HTML tags? Why important?
Ans: Semantic tags clearly describe their meaning to both browser and
developer.
Examples: <header>, <nav>,<article>, <footer>.

Q2: What is the difference between <div> and <span>?
Ans: <div> is a block-level element. It takes full width and starts on a new
line. Used for layout sections.
<Span> is an inline element It takes only as much width as 
needed. Used to style small parts of text.

Q3: Difference between block-level and inline elements?
Ans: (Block-level) Starts on new line, take full width. 
Example: <div>, <p>, <h1>, <section>.
(Inline) Do not start new line, take only required width.
Examples: <span>, <a>, <img>, <strong>.
 
Q4: What is the purpose of DOCTYPE declaration?
Ans: DOCTYPE tells the browser which version of HTML is used. Without it,
browser goes into "quirts mode" and layout may break.
For HTML5 it is just <!DOCTYPE html>.

Q5: Difference between id and class attribute?
Ans: (id) must be unique on a page. Used to identify one specific element.
Selected in CSS/JS with #id.
(Class) can be used on muitiple elements Used to group elements.
Selected in CSS/JS with .class.

Q6: How to create a form? Common input types?
Ans: Use <form> tag. action defines where data is sent, method is GET or POST.
Common inputs: text, email, password, radio, checkbpx, submit, data.

Q7: What are meta tags and why are they used?
Ans: Meta tags are placed inside <head>. They do not display on 
page but give info to browser and search engines.
Used for: character set, SEO description, viewportfor mobile,
another info.

Q8: What is the purpose of alt attribute in <img>?
Ans: (alt)=alternate text. Shows text if image fails to load. Used by screen
readers for visually impaired users. Also helps SEO.

Q9: How to make an image clickable?
Ans: Wrap the <img> tag inside an <a> tag. Clicking the image will open 
the link.

Q10: Difference between JPG, PNG,SVG, WebP?
Ans: (JPG) Best for photos, Small size but loses quality.No transparency.
(PNG) Best for logos/graphics. No quality loss, supports transparency.
larger size.
(SVG) Vector format. Scales without losing quality.Best for icons.
(WebP) Modern format by Google. Smaller size than JPG/PNG with good
quality.

Q11: Semantic tags in HTML5 like header, footer, section, article?
Ans: They define the structure and meaning of content.
<header>: Top part of page
<footer>: Bottom part
<section>: Group of related content
<article>: Independent content like blog post.

Q12:Difference between script, async, defer?
Ans: <script>: Blocks HTML parsing until script loads and runs.
async: Downloads script while HTML parses. Run immediately after
download.Ordered not guaranteed.
defer: Downloads script while HTML parses. Runs after full
HTML parsings, in order.

Q13: How to embed audio and video in HTML5?
Ans: Use <audio> and <video> tags. Control attribute adds play/
pause buttons.

Q14: Difference between relative and absolute paths?
Ans: (Relative) Path from current file location.
Example: images/picjpg,../folder/file.html
(Absolute) Full URL from root.
Example: https://mysite.com/images/pic.JPG

Q15: What are data attributes data-*> Where are they used?
Ans: Custom attributes to store extra data in HTML. 
Format: data-name="value".
Accessed in Javascript using:
element.dataset.name. Keeps HTML valid.

Q16: Purpose of viewport meta tag?
Ans: Makes page responsive on mobile devices. Without it,
mobile browsers show desktop version zoomed out.

Q17: How to improve SEO using HTML?
Ans: (1). Use semantic tags: header,nav,main,article
(2). Add proper <title> and meta description
(3). Use alt attributes for images
(4). Maintain heading hierarchy: h1 > h2 > h3
(5). Make site mobile-friendly and fast.

Q18: Accessibility best practices in HTML?
Ans: (1). Add alt text to all images
(2). Use <lable> for form inputs
(3). Ensure keyboard navigation works
(4). Use good color contrast
(5). Use semantic HTML instead of div/span everywhere.

Q19: Differene between strond vs b, em vs i?
Ans: <strong> and <em> are seamntic. They show importance/
emphasis and screen readers stress them.
<b> and <i> are only visual. they make text bold/
italic without meaning.

