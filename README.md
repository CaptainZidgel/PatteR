# PatteR
Lua pattern realtime recognition, powered by [Vue](https://vuejs.org/) and [Fengari](https://fengari.io/).

Based on [RegExr](https://regexr.com)

## Roadmap
1. Make match groups work.
	Problem: The way the site works is by simply feeding your patterns into a string.gsub() function, with the replacemention function replacing the original match with the matched group between two HTML tags.  \
	The implication of this is that it deletes anything outside the match group. Examine the pattern `%s(%u)`, which looks for an upper case letter after a space, and the match group is the letter. The replacement function would chop off the space.  \
	Solution: Unsure.

2. Make the site look nice with CSS :)

