# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?
- List at least two concrete bugs you noticed at the start  
  (for example: "the secret number kept changing" or "the hints were backwards").

--- The game looks fine until I started playing. The buttons are very buggy, sometimes it works, sometimes it doesn't. The hint of
    is telling me the opposite of what it suppose to. The score was negative. The restart button doesn't reset the score. 

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
--- I used Claude on this project
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).
--- I had a problem running the pytest, I described the issue and what it suppose to happen. Lastly, I send the error code. AI was able to figure out and the problem was that I need to import sys and os.
- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).
--- Sometimes AI does more than I told, for example if I told AI to fix a specific part of the function. It would fix all the problem of the function.

---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
- Did AI help you design or understand any tests? How?

---

## 4. What did you learn about Streamlit and state?

- In your own words, explain why the secret number kept changing in the original app.
- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?
- What change did you make that finally gave the game a stable secret number?

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
- What is one thing you would do differently next time you work with AI on a coding task?
- In one or two sentences, describe how this project changed the way you think about AI generated code.
