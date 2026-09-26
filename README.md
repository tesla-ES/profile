# Dr. Ahmed Abuzaid — Personal profile

Static, dependency-free résumé website for profile.tesla4.net.

## GitHub Pages
1. Create a public repository named profile in the tesla-ES account.
2. Upload index.html, CNAME, .nojekyll and Dr_Ahmed_Abuzaid_Resume.docx at the repository root. Do not upload the ZIP itself.
3. Settings → Pages → Deploy from a branch → main → / (root) → Save.
4. Set Custom domain to profile.tesla4.net.
5. In Cloudflare DNS, add CNAME: Name profile; Target tesla-es.github.io; Proxy DNS only; TTL Auto. If profile already exists, edit the existing record rather than adding a conflict. Preserve erp and mail records.
6. Enable Enforce HTTPS in GitHub once the certificate is ready.

The contact details and downloadable document come from the supplied résumé. They will be publicly accessible when deployed.
