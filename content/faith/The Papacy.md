---
title: The Papacy
description: The living Pope, papal audiences and the Christian-only favours Rome can grant.
tags:
  - faith
---

# The Papacy

> Game as of **30 June 2026** (beta). Details may change.

Rome is a living institution in the background. A Christian ruler can ask the Pope for favours that no secular lord can grant, while Muslim and Jewish rulers use different faith systems and are not subject to papal excommunication.

![[papacy-screen.png]]
*The papacy screen shows the current Pope, his attitude and available requests.*

## A living office

```mermaid
stateDiagram-v2
    [*] --> Reigning
    Reigning --> Conclave: the Pope dies
    Conclave --> Reigning: a new Pope is elected
    Reigning --> Chronicle: reign recorded
```

Popes age, die and are replaced. The current Pope has his own standing toward you, which affects how likely requests are to succeed.

## Papal favours

Christian rulers can request:

| Request | Typical use |
|---|---|
| Blessing or favour | Improve legitimacy, piety or relations with Rome |
| Divorce | End a politically bad marriage through Church approval |
| Legitimation | Make a [[Bastards|bastard]] eligible as a true heir |
| Campaign or crusading support | Seek papal backing for holy war |
| Donation | Spend gold to improve standing with Rome |
| Petition | Ask Rome for support in a difficult moment |

You get **one papal audience per season**, so timing matters. Many requests also cost gold, piety or political capital.

## Who answers to Rome

Only Christian rulers use papal favour and excommunication. Muslim rulers use the Umma-facing religious frame, and Jewish rulers use the Aljama-facing frame. This is not just flavour: faith changes marriage rules, secular title eligibility and which religious sanctions apply.

See [[Faith and Religion]] and [[Doctrines and Excommunication]].

## Staying in favour

A pious, generous and lawful Christian ruler finds Rome easier to work with. A tyrannical or impious ruler risks the opposite: papal hostility and excommunication pressure.

## Tips

- Save gold before asking for costly papal help.
- Do not waste the once-per-season audience on a low-value request.
- Use papal legitimation when succession is the real danger.
- Muslim and Jewish starts should plan around their own faith rules instead of relying on Rome.

---

*Next: [[Doctrines and Excommunication]] - Related: [[Faith and Religion]], [[Bastards]].*
