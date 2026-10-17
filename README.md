# etymlens

# The Abnihilisation of the Etym 

### Individuation, superposition and concealment in Wake-trained language models

> *"two thinks at a time"* — Finnegans Wake

**Draft:** v2, 2026-10-14 |
**Repo:** `etymlens`
**Depends on:** the wake2vec model lineup. **Requires no new training.**

A model trained on Wakean portmanteaux might have two routes available for the same string: the decomposition inherited from its base tokenizer and the injected whole-form representation. If one route dominated, the result could be described as a collapse. If both remained active, perhaps the model was maintaining a kind of superposition. And if the generated token appeared only at the final stages of the forward pass, with no convincing history in the preceding layers, the output might conceal the fact that the internal competition had never resolved cleanly.

The emitted token has no history.

v1 asked *which reading wins, and at what depth*. It defined `abnihilisation depth` as the layer where the injected whole-form reading overtakes the etymological one, and treated non-resolution as a null.

That framing assumes resolution is the outcome of interest. For Joyce it is the opposite. A portmanteau asks the reader to entertain several possibilities at once, **sometimes without permitting a settlement**. If the competition is the point, then holding is the phenomenon and collapse is the failure — in either direction. Collapsing onto the injected row is not success; it is a different way of settling.

**Two further points reshaped v2.**

The model is nonetheless *under pressure to settle*, because it must emit a token. So the output is a lossy and actively misleading readout: it can present as settled while the internals held, present a compromise, or present fluent nonsense that conceals that nothing resolved. The output cannot be used as evidence about the internal state, which is the argument for the method rather than an inconvenience to it.

And the deepest reframing: **does interference destroy the etym, or is interference what makes it visible in the first place?** In an uncontested context the subword reading is not a reading at all; it is simply the processing, invisible as such. It may become separable — an *etym*, a thing that could have been otherwise — only when something contests it. v2 takes this as RQ1 rather than as a remark.
