# 24x7 Home Care

A lightweight static website for a senior-care service. It is designed to deploy directly to GitHub Pages—no build process, database, or server is required.

## Contact form

The form uses [FormSubmit](https://formsubmit.co/) as a no-backend email relay. It sends the enquiry to `kinagianooj@gmail.com` and sends the visitor the supplied automatic acknowledgement included in `index.html`. FormSubmit's CAPTCHA remains enabled because its autoresponse feature depends on it; after submission, visitors return to the site home page.

On the first form submission after publishing, FormSubmit will email the destination inbox for activation. Open that email and approve the form; future submissions will then be delivered. Before using the site for real enquiries, update the privacy language and contact details to match the organisation and applicable laws.

## Publishing with GitHub Pages

1. Create a GitHub repository and upload these files to its default branch.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select the default branch and `/ (root)`, then save.
4. GitHub will show the live website address once deployment completes.

## Images

The site uses remote images from Unsplash. Unsplash says its free library is available for commercial and non-commercial use under its license; the footer links to the license. Confirm any additional rights appropriate to the final commercial use before launch.

