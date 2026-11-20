Sheraz Proposal SEO starter files

1. Copy public/robots.txt and public/sitemap.xml into your project's public folder.
   Deploy to Vercel. They should then be available at:
   https://sherazproposal.vercel.app/robots.txt
   https://sherazproposal.vercel.app/sitemap.xml

2. Add the metadata in metadata-head-snippet.html to the homepage <head>.
   If using Next.js App Router, set metadataBase, title, description, openGraph
   in app/layout.tsx instead. Do not paste raw <meta> tags into the body.

3. Ensure the homepage has visible, crawlable text containing the brand name
   "Sheraz Proposal", plus a clear H1 and useful page content.

4. In Google Search Console, add/verify the domain or URL-prefix property,
   submit https://sherazproposal.vercel.app/sitemap.xml, inspect the homepage,
   and request indexing.

Important:
- These files do not guarantee indexing or a particular Google result.
- Google may continue showing the vercel.app host as the site's URL/breadcrumb.
  A custom domain (e.g. sherazproposal.com, if available and owned by you) is
  needed if you want a branded domain instead of vercel.app.
- Search title/snippet are selected by Google and may differ from metadata.
- A robots.txt file does not force indexing; it only gives crawl directives.
