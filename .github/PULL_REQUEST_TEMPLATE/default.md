# what's this about?

[TCX-](https://kaligo.atlassian.net/browse/TCX-)

# design



# caveats



# impact
<!-- Does this PR have changes which rely on the credit internal_information?
Check if we need to reload the attributes in the sender and if it will affect bonus credit -->


# test cases



# notes
For new sender and receiver, please update this [notion page](https://www.notion.so/kaligo/API-Loyalty-Programs-Reprocessable-a2374a0620b94daab6aa466cf1800112)

For **migrations where columns are being removed/dropped**, please read [this guide](https://www.notion.so/kaligo/Production-deployment-guide-when-dropping-columns-1ba31c5427fd8074bdd9f1552c4ebb03) first before merging!

# deployment notes

- [x] revertable?

# observability
Ask ourselves:
- Does this PR have any important events, errors, or warnings we can track?
- Do we need to set up alerts for potential issues?
- Having some monitoring panels would be helpful for identifying anomalies and trends?