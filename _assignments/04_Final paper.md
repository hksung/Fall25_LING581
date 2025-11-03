---
type: assignment
date: 2025-11-04T23:59:00+3:30
title: '3. Assignment'

due_event: 
    type: due
    date: 2025-11-21T23:59:00+3:30
    description: '3. Assignment'
---
Each group should listen to and learn other students' research interests by actively listening to 8 presentations (not your own group) and write summaries. This is a graded assignment: 50 points total (10% of final grade).

{% assign pdf = '/Files/Assignment.pdf' %}

<!-- Inline preview (with fallback) -->
<object
  data="{{ pdf | relative_url }}"
  type="application/pdf"
  width="100%"
  height="800">
  <p>
    PDF preview isn’t available in this browser.
    <a href="{{ pdf | relative_url }}" target="_blank" rel="noopener">Open the PDF</a>.
  </p>
</object>

<!-- Download + open in new tab -->
<p>
  <a href="{{ pdf | relative_url }}" download>Download PDF</a>
  &nbsp;|&nbsp;
  <a href="{{ pdf | relative_url }}" target="_blank" rel="noopener">Open in new tab</a>
</p>
