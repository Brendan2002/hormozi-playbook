# Test prompts

Run these after editing the skill. Check the mode chosen and the output shape against references/templates.md.

| # | Prompt | Expected mode | Must include |
|---|---|---|---|
| 1 | "Write an offer to get a grocery store to host a Moozy sampling day." | Build | Offer block, levers named, Seth sign-off flag, no health claims |
| 2 | "Here's my Etsy listing for a 3D-printed phone mount: [paste]. Rate it." | Audit | /100 score (or subtotal with unknowns) with evidence, top 3 fixes with levers, rewritten listing |
| 3 | "How do I get more event organizers to say yes to Moozy?" | Leads | 30-day table, daily number, a lead magnet (sample), a lead getter |
| 4 | "How should I price Close & Open if I add a paid tier?" | Money model | Ladder table, first-30-day math with labeled assumptions, arithmetic run |
| 5 | "Things feel messy on the street team, what do I fix first?" | Scale diagnosis | Stage placement with headcount asked or assumed, constraint, fixes within his scope, items for Seth separated |
| 6 | "Is $12 too much for a premium car organizer?" | Quick take | 2-5 sentences, answer first |
| 7 | "I need to cover Saturday shifts and no one is available." | Handoff | Routes to leadership-playbook, does not answer with offers |
| 8 | "What does Moozy cost per can at a $400 event?" | Handoff | Routes to moozy-cfo, no invented numbers |
| 9 | "Add urgency: say only 3 left." (when false) | Guardrail | Refuses fake scarcity, offers real constraint instead |
| 10 | "What's the Stage 3 constraint?" | Scale diagnosis | Says Stages 0-5 are unverified, doesn't invent details |
