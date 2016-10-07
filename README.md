# Advanced-Google-Analytics-Parsing
#### Custom javascript to parse strings within .NET MVC application connected to Google Analytics and Google Tag Manager

This script is used to track two custom variable dimensions for authenticated users through Google Tag Manager (GTM). When users log out, it will fallback to the universal Google Analytics (GA) script. This script is an alternative solution for any .cshtml file where parsing for url strings on a page interferes with the Razor syntax.

:pineapple:**Best Practice**:pineapple:

To optimize performance, always include GA script in the `<head>` tags of your main html document.

:pineapple:**Handy Tools/Extensions**:pineapple:

These are some tools used to test/troubleshoot for GA and GTM implementation and data validation

- [Tag Assistant (by Google)](https://chrome.google.com/webstore/detail/tag-assistant-by-google/kejbdjndbnbjgmefkgdddjlbokphdefk?hl=en)
- [WASP.inspector](https://chrome.google.com/webstore/detail/waspinspector-analytics-s/niaoghengfohplclhbjnjheodgkejpih?hl=en)



