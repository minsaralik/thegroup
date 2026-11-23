THE GROUP - TEMPORARY HOMEPAGE

This is a simple static website. It does not require a database or paid hosting.

PUBLISH WITH NETLIFY
1. Create/sign in to a Netlify account.
2. Open https://app.netlify.com/drop
3. Upload the extracted folder containing index.html (or upload the ZIP if Netlify accepts it; folder upload is preferred).
4. Netlify will publish a temporary *.netlify.app address.
5. In the site's Domain management, add the custom domain: thebusinessgroup.com
6. Choose external DNS provider if asked, then follow the exact DNS instructions Netlify shows for your site.

PORKBUN DNS
In Porkbun > Domain Management > thebusinessgroup.com > DNS:
- Add/update the apex/root A record only with the value Netlify gives you. Netlify's standard external-DNS guide currently lists 75.2.60.5 for the apex.
- Add/update the www CNAME with the exact site-name.netlify.app target shown by Netlify.
- Do not delete MX or email-related TXT records. Remove only conflicting web/parking records if needed.
DNS changes can take several hours and sometimes up to 24-48 hours.

IMPORTANT
The page presents the listed ventures as future/planned concepts, not as currently operating businesses.
Before publishing, review the wording and replace or remove any venture names you do not want public yet.
