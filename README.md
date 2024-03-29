# Hugo Tech Blog Theme

## Forked from https://github.com/hugo-sid/hugo-blog-awesome

## Purpose

After doing a lot of research and looking at various open source Hugo blog platforms I was very unpleased with most that I found. I generally saw three types of themes:

1. Too complex of a visual design, attempting to be more of a resume website or portfolio website. Additionally, too complex from a technical sense with too many 3rd party integrations I don't want to have to support such as user comments. I'd like a very simple site to host from S3 with Cloudflare or S3 with AWS Shield, I don't want to spend my time on devops for a simple blog.

2. Unsupported with outdated dependencies such as 10 year old JQuery versions or having compressed JS libs or even `node_modules` checked in to source control and directly referenced in HTML files. Yikes!

3. Hard to read layout source files or vastly unoptimized for mobile.

I liked this theme the most of those which I studied and felt I could maintain a hard fork of it for my own purposes. There were a few things I've addressed. I'm not a huge fan of how the JS dependencies were included, although I felt I could easily update that. I also found a few bugs and places the Hugo API wasn't used quite right such as how some images were included, but have been working through fixes for that. The SASS based CSS files are a bit lenghty, if I have time I'll see if I can simplify those. Overal this was my favorite and a very well made blog platform, well done to the original author, and I hope to contribute back to the source eventually.
