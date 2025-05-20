### 1. Where would you fit my automated tests in my Recipe project development pipeline? Explain why.

I would fit my automated tests in my Recipe project development pipeline **within a GitHub action that runs whenever code is pushed**. The reason is because manually running them locally before pushing code isn't an automated process. Additionally, running them all after development is completed is counterintuitive to the concept of a development pipeline as you skip the testing altogether and go straight to launch.

### 2. Would you use an end-to-end test to check if a function is returning the correct output?

No.

### 3. What is the difference between navigation and snapshot mode?

The difference between navigation and snaapshot mode is that navigation analyzes a page when it loads, this excludes any sort of interaction the user might make that may impact any metrics calculated. Snapshot on the other hand, analyzes a page at its current state, therefore it can include any metrics that were changed as a result of any interaction the user has made to the webpage.

### 4. Name three things we could do it improve the CSE 110 shop based on the Lighthouse results.

1. `<html>` element does not have a `[lang]` attribute. As stated by Lighthouse, using this attribute can serve as an opportunity "to improve the interpretation of your content by users in different locales."
2. Document does not have a meta description. Meta descriptions may be included in search results to concisely summarize page content.
3. Properly sizing images. If we do so, we have the potential to save 718 KiB. Serve images that are appropriately-sized to save cellular data and improve load time.
