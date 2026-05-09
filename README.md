# Vacation Planner Prompt

A structured, detailed prompt that turns any AI assistant into a personal travel planner. Drop it into Claude, ChatGPT, Gemini, or any other LLM and get a complete, day-by-day vacation plan tailored to your group, budget, and interests.

---

## What it does

Most AI travel prompts give you generic advice. This one does not.

It works in two phases: first it collects everything it needs to know about your trip through a natural conversation, then it generates a full travel plan covering transport, accommodation, a daily itinerary with real restaurant names, a budget breakdown, and practical tips — all adapted to your specific group and travel style.

---

## What you get

- **Transport recommendation** — compares all options (flight, train, car, ferry) with costs, timings, and booking tips, then tells you which one to pick and why
- **3 accommodation proposals** — real hotels, B&Bs, or apartments with names, neighborhoods, prices, and honest caveats
- **Full day-by-day itinerary** — every day planned from morning to evening, with specific places to visit, real restaurants for lunch and dinner, dish recommendations, and end-of-day logistics
- **Budget breakdown** — cost estimates per person for every spending category, plus a total range with a contingency buffer
- **Practical tips** — 5 to 8 actionable tips on local customs, apps to download, what to book in advance, and traps to avoid

---

## How to use it

1. Open the file `vacation-planner-prompt.md`
2. Copy the entire contents
3. Paste it into any AI assistant as your first message
4. The AI will start asking you questions one by one
5. Answer naturally — the plan gets generated once all info is collected

Works with: Claude, ChatGPT, Gemini, Mistral, Llama, and any instruction-following model.

---

## Multilingual

The prompt instructs the AI to respond in whatever language you write in. Start the conversation in English, Italian, French, Spanish, German, Portuguese — it adapts automatically.

---

## Example output structure

```
Phase 1 — 7 questions collected conversationally

Phase 2 — Full travel plan:
  Section 1 — Transport recommendation
  Section 2 — 3 accommodation options
  Section 3 — Day-by-day itinerary (morning / lunch / afternoon / dinner / evening)
  Section 4 — Budget breakdown per person
  Section 5 — Practical tips
```

---

## Who it is for

- Anyone who wants a real plan, not a list of Wikipedia highlights
- Families, couples, solo travelers, groups of friends, seniors
- Budget backpackers and luxury travelers alike — the prompt adapts to your level
- People who hate spending hours on TripAdvisor and just want to be told what to do

---

## Files

| File | Description |
|---|---|
| `vacation-planner-prompt.md` | The prompt — copy and paste this into any AI |
| `README.md` | This file |

---

## Tips for best results

- The more honest you are about your group and budget, the better the output
- If you are traveling with young children or elderly people, say so explicitly — the itinerary rhythm changes significantly
- If the AI suggests a restaurant or hotel you cannot find online, ask it to suggest an alternative — it will comply
- You can ask follow-up questions after the plan is generated: "Can you find a cheaper accommodation?" or "What if it rains on day 3?" works fine

---

## Contributing

Have ideas to improve the prompt? Found a case where the output was weak? Open an issue or submit a pull request. Common areas for improvement:

- Better handling of multi-destination trips
- Cruise and road trip variants
- Budget-only or luxury-only simplified versions
- Region-specific prompts with deeper local knowledge

---

## License

MIT — free to use, share, modify, and build on. Credit appreciated but not required.

---

*Built with the belief that a good trip starts with a good plan, and a good plan starts with the right questions.*
