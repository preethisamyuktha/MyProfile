---
layout: demo
signoff: Adios!
---

# Create a Fork in GitHub

This is edited by Mridula Menon.

Merged the content from mridual and added new content.

[link for the new page](adding a page.md)

{{page.signoff}}

I am going to show how the numbers can be added using data files.

{% for item in site.data.demo %}

If you {{item.method}} to {{item.number}}, the result will be {{item.result}}

{% endfor %}