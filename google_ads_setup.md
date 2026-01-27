# Google AdSense Integration Guide

To integrate Google AdSense into your website and start generating revenue, follow these steps:

1.  **Sign Up for Google AdSense:**
    *   If you don't already have one, create a Google AdSense account. Visit [AdSense website](https://www.google.com/adsense/) and follow the sign-up process.
    *   You will need to provide your website URL and some personal information. Google will review your application, which might take a few days.

2.  **Get Your AdSense Code:**
    *   Once your account is approved, log in to your Google AdSense account.
    *   Navigate to the "Ads" section. Here you can create different types of ad units (e.g., display ads, in-feed ads, in-article ads).
    *   Configure your desired ad unit and then click "Get code." You will be provided with a JavaScript code snippet.

3.  **Place the AdSense Code on Your Website:**
    *   **Auto Ads (Recommended for beginners):** If you enable Auto Ads in your AdSense account, you only need to place one piece of code into the `<head>` section of your `index.html` and `forum.html` files. Google will then automatically place ads where they are likely to perform well.

        Example of Auto Ads code to place in `<head>`:
        ```html
        <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-YOUR_PUBLISHER_ID"
            crossorigin="anonymous"></script>
        ```
        **Remember to replace `ca-pub-YOUR_PUBLISHER_ID` with your actual publisher ID from your AdSense account.**

    *   **Manual Ad Units:** If you want more control over ad placement, you will copy the specific ad unit code and paste it directly into the `<body>` section of your `index.html` or `forum.html` files where you want the ad to appear. For example, you might place an ad unit within a `<section>` or `<div>`.

        Example of a manual display ad unit code:
        ```html
        <ins class="adsbygoogle"
            style="display:block"
            data-ad-client="ca-pub-YOUR_PUBLISHER_ID"
            data-ad-slot="YOUR_AD_SLOT_ID"
            data-ad-format="auto"
            data-full-width-responsive="true"></ins>
        <script>
            (adsbygoogle = window.adsbygoogle || []).push({});
        </script>
        ```
        **Remember to replace `ca-pub-YOUR_PUBLISHER_ID` and `YOUR_AD_SLOT_ID` with your actual IDs.**

4.  **Monitor Performance:**
    *   After placing the code, it might take some time for ads to start appearing.
    *   Regularly check your AdSense account for reports on impressions, clicks, and earnings.

**Important Considerations:**

*   **Content Quality:** Ensure your website has valuable, original content. Google AdSense policies are strict about content quality.
*   **User Experience:** Don't overload your pages with too many ads. This can negatively impact user experience and potentially lead to lower earnings or policy violations.
*   **Compliance:** Always adhere to Google AdSense program policies.
*   **Testing:** It's recommended to test different ad placements and ad unit types to see what works best for your audience.

Good luck with your new Edmonton website and AdSense integration!
