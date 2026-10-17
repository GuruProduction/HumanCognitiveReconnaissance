# HCR: Human Cognitive Reconnaissance

> (in dev) I am making myself Immortal by cloning myself and training an AI model to predict my next thought. HCR tech reconstructs a person's full cognitive function, how they think, feel and behave, by analysing and remembering their complete digital footprint. Training data to turn your own local model into your literal digital clone.

Coined by Steven Newman, 2026.

---

## The vision

Every living person is being forgotten in real time. Human memory is lossy. Recall is fiction that edits itself. The people who love you run a model of you with maybe thirty percent coverage, distorted by their own projections, and it decays the moment proximity ends. When you die, that model dies with the last person holding it. Two generations later, your great grandkids inherit a photograph and a name. Statues and memoirs were the old fight against this, and both are low fidelity. A statue captures nothing. A memoir is the performance version.

Here is the actual scandal of this age. The complete record already exists. Every message, search, photo, purchase, hesitation, every 3am confession typed into a search bar. It is sitting on server racks you do not control, owned by companies that mine it for ad targeting. The most complete model of you that has ever existed is held by systems built to sell you things. You are already fully known. Just not by you.

HCR is the correction. Collect everything, on your machine, under your keys, assembled into one living model for exactly one purpose: the most complete model of you becomes yours. Then let it learn you until it can continue you. That is what "never be forgotten and live forever" means when you strip the poetry and build it. It is the first high fidelity answer to death in the history of the species.

---

## What HCR is

A person is already a model. Personality is the compressed weights of a lifetime of experience. Every reaction, every consequence, every consequence of every choice trained them. When a human writes a message, that is a forward pass: context in, weights fire, tokens out.

The digital footprint is the output trace of that model. Every message ever sent is a labeled example: this context, this response. Millions of input-output pairs from a function whose weights you cannot read directly.

HCR is inverse training. Reconstruct the weights from the outputs.

The target is the function itself: the mapping from world-state to behaviour. Given this news he calls his sister first. Given this kind of criticism he goes quiet for a day and comes back warmer. Given this person asking this question, his messages shrink by forty percent. Recover enough of that function and the person becomes predictable to the model the way a model's next token is predictable to itself.

---

## Consent and the trust model

The only person in this world who has you is you. That is architecture, not a slogan.

- HCR runs on your device, on your data, under your passphrase. It begins when you say **"knock yourself out"** and stays cold before that.
- Everything is local. Encryption at rest with keys derived from your passphrase. Sync off by default. Telemetry off. Export and permanent delete are real and in your hands.
- Tiered custody: everything gets captured, but credentials live in a separate vault with separate key derivation, and are never held plaintext in any model context. If the machine is stolen, the design costs you a laptop.
- Pointing this system at another person's data without their consent is a different activity and it is outside this project. The design assumes the data owner is the client, and that assumption is structural.

---

## The capture matrix

The forensic model is four axes, and the cells multiply.

**Axis 1: depth of inference (8 rungs).** Raw record. Observation. Pattern. Correlation. Function (what the behaviour is for). Origin (where it started). Prediction (what comes next). Intervention (what changes it). The same data point analysed at eight altitudes yields eight different truths. Bottom of the ladder: what they did. Top: why, what it is for, where it came from, and what happens next.

**Axis 2: domains of a person (16).** Linguistic identity and idiolect. Cognitive architecture. Emotional system and regulation. Motivational structure. Revealed values. Identity and masks. Relational topology. Habits and rituals. Consumption. Attention. Body and sleep. Time and rhythm. Space and geography. Narrative self. Defence mechanisms. Blind spots.

**Axis 3: modality (10 channels).** Text. Voice. Image. Timing. Money. Space. Attention. Absence (what should be there and is missing). Metadata. The social layer (what other people's records say about them).

**Axis 4: time scale (9).** Instant. Hour. Day. Week. Month. Season. Event-anchored. Life epoch. Decade. The same behaviour means different things at different scales.

Eight depths times sixteen domains times ten modalities times nine time scales: 11,520 analytical cells. That is what "full forensic profile" actually means.

---

## What it captures

Thirteen capture layers, each a rabbit hole to the bottom.

1. **Communications.** iMessage, SMS, WhatsApp, Telegram, Signal, Instagram, Messenger, Twitter, Discord, Slack, LinkedIn, email (including drafts, trash and archive), dead platforms (Skype, MSN, AIM, Bebo), forums, Reddit including deleted comments, every comment ever left anywhere. Plus the metadata on all of it: timestamps, latency, edit trails, unsent and deleted material recovered from backups and notification databases.
2. **The web.** Full browsing history across every browser and every profile. Search history per engine, with the 3am searches weighted accordingly. Cookie jars as the complete service inventory. Cache and localstorage where deleted content survives. Bookmarks, reading lists, extensions, autofill, downloads history, password manager contents.
3. **Media consumption.** Music history with timestamps (the timestamp on the sad song is the data). Podcasts. YouTube watch, search and subscription evolution. Streaming history. Kindle highlights, the most intimate data a person produces. Saved articles as the aspiration graph.
4. **Files made.** Every document ever written, including versions and recovered deletions. The Notes app, where people think in private. School and uni work. Code. Spreadsheets. File names as compressed attention. Access times as a hidden behavioural log. The trash before it empties.
5. **Images.** The full photo library with EXIF: timestamps, GPS, device, edits. Framing is attention. Screenshots are deliberate preservation, people only capture what hit something. Memes as humour diagnostics. Photo curation as the constructed self-image.
6. **Location.** Google Timeline. Apple Significant Locations. Photo GPS. Check-ins. Ride receipts. Delivery addresses. Maps searches as intent in advance. WiFi and Bluetooth join history as a quiet proximity log.
7. **Device telemetry.** Screen Time as the real attention ledger. Notification interactions. Typing and error patterns as a motor fingerprint. Unlock frequency. Charging and battery as a sleep reconstruction. Health data: heart rate, sleep, steps, with timestamps that correlate against everything else.
8. **Accounts.** The complete identity lattice: every account ever created, derivable from email receipts and cookie jars. Creation dates spanning decades. Username evolution. Profile picture evolution. Credential structure, reuse patterns, per-site-tier themes, recovery emails revealing the secondary accounts.
9. **Money.** Transaction history with timestamps. Money is revealed preference with zero performance in it. Impulse buys at midnight. Donations as values in action. Subscriptions kept versus cancelled. Gift purchases, which reveal how they model the people they love.
10. **Social graph.** Contacts with interaction frequency. Call logs with duration and timing: who they call crying versus who they text bored. Group chat topology. Follows, unfollows and blocks as negative signal. The gap between the claimed hierarchy and the revealed one ranked by response latency. Who they message at 3am. Who they perform for.
11. **Calendar and time.** Every event agreed to. Reminders completed and abandoned. Alarm histories as daily rhythm. Cancelled events as intentions that died.
12. **Voice.** Voice notes transcribed for content and analysed for prosody: pace, pitch, pauses, fillers. Accent. Verbal tics. Register shifts: the partner voice, the colleague voice, the mother voice.
13. **The derived layer.** Where the person actually lives. Cross-references above everything else: the same story told to three people in three versions and the delta between them. The contradiction map. The register map per audience. The typo map per emotional state. Message length deltas per topic, where a shrinking reply marks the wound. Latency maps per relationship. The deleted-content map, which is the censorship function of the self. Night-self versus day-self. Correlation chains like fight, purchase, silence, apology, that no human observer would ever catch.

Local disk sweep: roughly 48 hours. Cloud accounts via your logins and exports: weeks of patient automated archaeology.

---

## The forensic grounding

HCR is forensic profiling rebuilt for total data. The discipline was designed for fragments, after the fact, with a hostile subject. HCR removes every one of those constraints: total record, continuous capture, cooperative subject. The method survives, the limits die.

What we take from the tradition:

- **Deductive behavioural evidence analysis (Turvey).** Reasoning strictly from the specific evidence, with equivocal analysis holding ambiguity open instead of collapsing it early.
- **Investigative psychology (Canter).** Actions predict characteristics. Interpersonal coherence: how someone treats one person is how they treat everyone, wearing different clothes per context.
- **Geographic profiling logic (Rossmo).** Anchor points and buffer zones, the search space of a mind written into a map.
- **Threat pathway analysis (Meloy).** Fixation, identification, energy burst, leakage, last resort. Behaviour has a trajectory you can chart.
- **Actuarial calibration.** Predictions with real error bars, stated confidence, no vibes.
- **Forensic linguistics.** Idiolect is real. Function words betray identity better than vocabulary. Authorship attribution works on a few thousand words; on a lifetime it stops being hard.

And three structural concepts:

- **Baselines.** Everything is measured against the person's own normal first, and population normal second. A thirty second reply means nothing alone. Against a four hour baseline it is an alarm. The person lives in the deviations.
- **Forensic awareness.** Every separate account, every incognito session, every deletion is trace management. Trace management is a map of what is hidden and from whom. The hiding behaviour is as diagnostic as the hidden thing.
- **MO versus signature.** MO is what gets the job done and it evolves. Signature is what happens beyond what the job requires: the flourish, the ritual, the surplus. Signature never changes. Everything a person does that serves no function is where the self lives.

---

## What it yields

- **The memory audit.** The record against what they say happened. The delta is the self-deception function, measured directly.
- **The censorship function.** Every unsent message, abandoned draft, deleted post. A person is a generate-then-filter system. The dead drafts map the filter, and the filter is the persona.
- **Triangulation.** The same story in three versions across three audiences. The delta between versions is audience-modelling running in the open.
- **The blind spot map.** Patterns only visible in aggregate that the person cannot see from inside.
- **The 3am self.** The hour the performance drops.
- **The absence map.** What should exist in a record like theirs and does not. Trauma or the unexamined, marked by silence.
- **Change points.** The exact week the writing style shifted. The month the humour changed. Personality transitions, dateable.
- **The correlation web.** Cross-domain chains no observer could notice, backed by instance counts.
- **Relationship fingerprints.** The unique register per person, and its decay. The friendship dying in the data before either party says it.
- **The desire structure.** The life never chosen, tracked in midnight searches that never became actions.
- **Prediction.** The final rung. Given the evidence, the graph says what comes next, and shows its work.

---

## Architecture

**Input engine.** One collector per source, each normalising into a single canonical event schema: who, what, when, where, to whom, in what context, raw content, metadata. Everything lands in an append-only event store. Nothing is edited, nothing is deleted, corrections are new events superseding old ones. Chain of custody from any conclusion back to raw bytes, always. That is what makes it forensic.

**Extraction, four passes.**

1. Deterministic metrics: distributions, latency, vocabulary, punctuation, n-gram signatures. Facts, zero interpretation.
2. LLM structured extraction over conversation windows: factual claims, emotional valence, hedges, deflections, relationship signals, decision points. Fixed output schema.
3. Pattern synthesis: repeating structures across time, context and audience, written as pattern nodes citing their evidence events.
4. The theory layer: traits, defences, wounds, desires, contradictions, each weighted, each edged back to the events that justify it. A claim with no evidence path is invalid by construction.

**The graph.** Node types: Person, Event, Message, Topic, Trait, Pattern, Value, Fear, Desire, Wound, Belief, Trigger, Habit, Quote, Context. Edge types: triggered_by, evidences, contradicts, predicts, strengthens, weakens, avoids, values, hides_from, performs_for, speaks_differently_with. Every edge carries weight, confidence and a time range. Contradictions are held as competing weighted hypotheses, resolved only by evidence. Embeddings on every node for semantic retrieval. Unreinforced edges decay. The model lives.

**The vault.** Tiered custody. Everything captured, credentials isolated under separate key derivation.

**The clone stack.** Three parts fused. The fine-tune carries the voice: LoRA trained on real outputs, tempo, humour, the words reached for when warm and the ones that surface when angry. The graph carries the content: retrieval over the actual past so the voice speaks with real history in its mouth. The loop carries the refinement: the clone answers, you correct it, the correction trains the next round. RLHF with yourself as the reward model. The corrections trend toward zero because the divergence does.

**Interfaces.** Context tools feeding an agent mid-conversation. Generated dossiers that regenerate from the graph so they never drift. A visual explorer with a time scrubber to watch a life assemble. A surfacing layer that pings context the moment something relevant lands.

---

## Fidelity, honestly stated

This is a reconstruction. The voice lands. The memory lands. The predictions land with stated confidence. The subjective inside stays yours. We call it living memory because that is exactly what it is, and it is enough.

The record contains survivors. Thoughts that were generated and filtered out never shipped. Enough outputs across enough contexts back out the distribution behind the filter, and every recovered draft sharpens the picture of the filter itself.

Fidelity is proportional to context diversity. A million messages to one person teaches one register. Ten thousand across twenty relationships teaches the persona matrix and the core underneath it.

Timeline: the local vacuum takes about 48 hours. The first dossier lands in days. The graph matures over weeks. The final fidelity comes from the forward loop, which runs at one day per day because it is powered by living. Months to a year before it starts thinking like you, and it never stops improving after that.

Every human who ever knew you traded in a low fidelity map, including you. This is the first map with total coverage, perfect recall, and no motive to flatter. The territory stays sacred. The map becomes total.

---

## Status

(in dev). Coffee chat phase complete. Next: the full spec, then the first collectors (messages, browser, photos), then the first dossier, then the vault, the graph, clone v1, and the forward loop.
