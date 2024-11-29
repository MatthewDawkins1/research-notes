**Tags:** #Daily-Notes
# <% moment(tp.file.title,'YYYY-MM-DD').format("dddd, MMMM DD, YYYY") %>

### What I plan to do:
Whats the plan of attack for today?<% tp.file.cursor() %>
### What got done:
What actually got done today?
### Whats left open:
What is left open from today that needs to be picked up in the future:
- Work
- Thoughts
- etc ...
### Misc:
Everything else :) REMOVE IF NOTE NEEDED

<<[[<% fileDate = moment(tp.file.title, 'YYYY-MM-DD').subtract(1, 'd').format('YYYY-MM-DD') %>]] | [[<% fileDate = moment(tp.file.title, 'YYYY-MM-DD').add(1, 'd').format('YYYY-MM-DD') %>]] >>