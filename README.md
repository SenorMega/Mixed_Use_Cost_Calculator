Mixed-Use TIC/LLC Cost Calculator

A lightweight, interactive web application designed to calculate fair ownership splits for mixed-use real estate purchases.
This tool is specifically built for groups purchasing mixed-use buildings (e.g., a commercial ground floor with residential flats above) through a Tenancy in Common (TIC) or Limited Liability Company (LLC) structure.


The Problem It Solves

When buying a mixed-use building, splitting the purchase price strictly by square footage is often unfair. In many markets (like San Francisco), residential square footage is valued much higher than commercial square footage.
This calculator uses a Weighted Square Footage Methodology. It allows you to assign different market rates to residential and commercial spaces, calculates the "weight" of each unit, and determines the exact percentage of the total purchase price each partner should pay.


Features

- Real-time Calculations: Adjust the total purchase price and see the cost splits update instantly.
- Valuation Sliders: Easily tweak the estimated price-per-square-foot for both residential and commercial spaces.
- Customizable Units: Add up to 5 units, categorize them as Residential or Commercial, and input their specific square footage.
- Standalone Architecture: Built entirely in a single index.html file using React and Tailwind CSS via CDNs. No build step or server required.


Technologies Used

- HTML5: Single-file structure.
- React 18: For reactive state management and UI components (loaded via CDN).
- Babel (Standalone): To compile JSX directly in the browser.
- Tailwind CSS: For styling (loaded via CDN).
- Lucide Icons: (Converted to inline SVGs for the standalone setup).


How to Host on GitHub Pages

Because this application is contained within a single index.html file, hosting it on GitHub Pages takes less than a minute:

1. Create a new repository on GitHub.
2. Upload the index.html file to the root of the repository.
3. Go to the repository Settings > Pages.
4. Under "Build and deployment", set the source to Deploy from a branch.
5. Select the main branch and click Save.
6. Your calculator will be live at https://[your-username].github.io/[repository-name].

Embedding in Squarespace (or any website)

Once hosted on GitHub Pages, you can embed this calculator seamlessly into your personal website using an iframe.

If using Squarespace:
- Add a Code Block to your page.
- Paste the following HTML, replacing the src URL with your live GitHub Pages link:

<iframe 
  src="[https://your-username.github.io/your-repo-name](https://your-username.github.io/your-repo-name)" 
  width="100%" 
  height="1300px" 
  style="border:none;">
</iframe>

Note: Depending on your Squarespace template, you may need to adjust the height attribute to ensure the calculator fits perfectly without scrolling.
