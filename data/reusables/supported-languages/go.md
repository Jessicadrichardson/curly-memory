| Go {% ifversion fpt or ghec %}| {% octicon "check" aria-label="The check icon" %} | {% octicon "check" aria-label="The check icon" %} | {% octicon "check" aria-label="The check icon" %}<br>Go modules | {% octicon "check" aria-label="The check icon" %}<br> Go modules | {% octicon "check" aria-label="The check icon" %} | {% octicon "x" aria-label="The X icon" %} |{% elsif ghes > 3.1 %}| {% octicon "check" aria-label="The check icon" %} | {% octicon "check" aria-label="The check icon" %}<br>Go modules | {% octicon "check" aria-label="The check icon" %} | {% octicon "x" aria-label="The X icon" %} |{% elsif ghes %}| {% octicon "check" aria-label="The check icon" %} | {% octicon "x" aria-label="The X icon" %} | {% octicon "check" aria-label="The check icon" %} | {% octicon "x" aria-label="The X icon" %} |{% elsif ghae %}| {% octicon "check" aria-label="The check icon" %} | {% octicon "check" aria-label="The check icon" %} | {% octicon "x" aria-label="The X icon" %} |{% endif %}