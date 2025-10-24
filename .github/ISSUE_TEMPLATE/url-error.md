---
name: Periodic URL Checker URL Error Template
about: URL Error template for the periodic URL checker to use to open a repo issue if it finds errors
title: Broken URLs found in the course!
labels: url-error
---

URLs in this course were just checked and some broken URLs were found.

**Number of errors:** {{ env.ERROR_NUM }}
**File where errors are:** [URL checks file here]({{ env.FILE_URL }})
