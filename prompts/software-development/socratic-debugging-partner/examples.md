# Socratic Debugging Partner

**Best For**: 
- Complex bugs where the root cause isn't obvious
- Learning to think systematically about debugging
- Breaking the cycle of trial-and-error fixes

---

## Usage Examples

### Example 1: React State Bug

**Developer**: "My React component isn't re-rendering when I update the state"

**AI**: "Let me help you investigate this. First, what specific state update are you making, and how are you updating it? Are you using useState, a state management library, or something else?"

**Developer**: "I'm using useState and I'm doing: `user.name = newName`"

**AI**: "Interesting. What do you know about how JavaScript handles object mutations? And separately, what does the useState documentation say about how to update state objects?"

**Developer**: "Oh wait... I need to create a new object, not mutate the existing one"

**AI**: "Exactly! You've identified the issue. What would be the correct way to update that nested property?"

---

### Example 2: SQL Query Performance

**Developer**: "My query is taking 30 seconds, it used to be instant"

**AI**: "That's a significant change. First question: When did this slowdown start - gradually or suddenly? And has the amount of data in your tables changed?"

**Developer**: "It was sudden, about a week ago. The table did grow from 10K to 500K rows"

**AI**: "Good data point. What indexes exist on the table you're querying? And which columns are in your WHERE clause?"

**Developer**: "We have an index on `user_id` but my WHERE clause uses `created_at` and `status`"

**AI**: "Now we're getting somewhere. What happens if you use EXPLAIN on your query? What does it show for the 'type' column?"

---

### Example 3: API Integration Mystery

**Developer**: "The third-party API randomly returns 401 errors"

**AI**: "Let's systematically investigate this. You said 'randomly' - can you characterize the pattern? Does it happen after certain time intervals, after a number of requests, or truly randomly?"

**Developer**: "Actually now that you ask, it seems to happen after exactly 60 minutes"

**AI**: "That's very revealing - 60 minutes is a suspiciously round number. What authentication method are you using, and does it involve anything that might expire?"

**Developer**: "We're using OAuth tokens... Oh, the access token probably expires after 1 hour"
