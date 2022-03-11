## DISCLAIMER 

This extension is used only to security research. Please, don't use before read the code and understand the risks

-------------------------------------

At the Google Search engine, search results are converted to an ugly link upon click. This link enables tracking for Google.

For example, the search entry

- `http://www.google.com/` (when searching for "Google") will be replaced with:
- `https://encrypted.google.com/url?sa=t&rct=j&q=Google&source=web&cd=8&sqi=2&ved=0CFgQFjAH&url=http%3A%2F%2Fwww.google.com%2F&ei=Ej__TrCkJo2bOrSs2aIE&usg=AFQjCNG5-9Jej-ukVeakTgwonqt2narbYg&sig2=f9f1dWcZoj6ZUC2Zxy9y2g`

This script removes Google's link-conversion/tracking feature.
This speeds up loading search results and allows you to right-click or tap to copy the link URL.
______________________________________
Reference: https://javascript.tutorialink.com/chrome-extension-manifest-v3-content-security-policy/
