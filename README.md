# Elite Space — Interior Design & Execution

A responsive, one-page website for Elite Space, focused on residential and commercial interiors around Amritsar, Punjab.

## Preview

Expected GitHub Pages URL after Pages is enabled and the workflow succeeds:

https://kharghsingh.github.io/khargh/

## Before launch

- Add the official WhatsApp business number in `index.html` in `const WHATSAPP_NUMBER=''`. Use digits only, including India's country code `91` followed by the 10-digit number.
- Replace inspiration photos with genuine Elite Space project photos where possible. Inspiration images are labeled as such and should not be represented as completed projects.
- Confirm that the described services and service area match what Elite Space can reliably deliver.
- The canonical and social-preview URLs are currently set to the expected GitHub Pages URL; update them if the deployed URL changes.

## Enable free GitHub Pages hosting

This site is designed for GitHub Pages on a public repository.

1. Open this repository on GitHub.
2. Select **Settings**.
3. Open **Pages** under **Code and automation**.
4. Under **Build and deployment**, choose **GitHub Actions** as the source.
5. Save the setting. The workflow in `.github/workflows/pages.yml` deploys the site when `main` is updated, or can be started manually from the Actions tab.
6. After the workflow succeeds, open the Pages URL shown in the workflow deployment environment.

A custom `.com` domain is optional and costs extra. Start with the free GitHub Pages address.
