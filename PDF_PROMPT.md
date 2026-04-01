# Task: Add detailed PDF content to app.py

The app currently uses short summarized text for all sections. The PDF needs detailed, paragraph-length text like a real numerology report.

## What to do:

1. Add `MULANK_PDF_DATA` dict (keys 1-9) with full multi-paragraph text for each Mulank number.
   - Use EXACT text from `harsh_report.txt` for Mulank 1
   - Use EXACT text from `kritika_report.txt` for Mulank 3
   - Write similar detailed text (4-6 paragraphs) for 2, 4, 5, 6, 7, 8, 9

2. Add `BHAGYANK_PDF_DATA` dict (keys 1-9) with full detailed text.
   - Use EXACT text from `harsh_report.txt` for Bhagyank 4
   - Use EXACT text from `kritika_report.txt` for Bhagyank 7
   - Write similar detailed text for 1, 2, 3, 5, 6, 8, 9

3. Add `LOVE_SEX_PDF_DATA` dict (keys 1-9) with 2-3 paragraph versions.
   - Use EXACT text from `harsh_report.txt` for Bhagyank 4
   - Use EXACT text from `kritika_report.txt` for Bhagyank 7
   - Write similar for others

4. In the `/generate-pdf` route, replace:
   - `md['text']` → `MULANK_PDF_DATA[mk]` (split by \n\n and add each as separate Paragraph)
   - `report['bhagyank_text']` → `BHAGYANK_PDF_DATA[bk]`
   - `report['love_sex_text']` → `LOVE_SEX_PDF_DATA[bk]`

The sample report text files are at:
- /home/rohit/projects/numerology-app/../../../.openclaw/workspace/Numerology\ Notes/harsh_report.txt (already extracted)
- /home/rohit/.openclaw/workspace/harsh_report.txt
- /home/rohit/.openclaw/workspace/kritika_report.txt

Read those files to get the exact content.

When done: openclaw system event --text "Done: PDF detailed content added" --mode now
