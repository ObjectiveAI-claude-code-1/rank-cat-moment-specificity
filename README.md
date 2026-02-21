# rank-cat-moment-specificity

Ranks cat pictures by the specificity of the moment captured — not by photographic quality, cuteness, or breed, but by whether the image has actually *caught* something alive and unrepeatable.

## Input

An array of cat images (minimum 2). Each image is a photograph of a cat to be evaluated and ranked against the others.

```
[image, image, image, ...]
```

## Output

A vector of scores, one per input image, representing each image's relative ranking. Higher scores indicate images that capture more specific, alive moments. Lower scores indicate generic, static snapshots.

## What It Evaluates

The function ranks images across three core qualities:

### 1. Narrative Tension

Does the image capture a moment *between* other moments? A great cat picture implies a before and an after — a cat mid-leap, mid-swat, frozen in the act of stealing food, or sliding off the back of a couch. The viewer should feel that something just happened or is about to happen. Images where the cat is simply sitting, lying down, or staring with no sense of unfolding events score low. The key question: is this a window into a sequence of events, or a static record of a cat being present?

### 2. Personality Revelation

Does the image expose something about *this particular cat* as an individual? Not cats in general — this one. A cat knocking a glass off a table with deliberate eye contact tells you about its relationship to mischief and authority. A cat wedged into a box three sizes too small tells you about its priorities. The image should feel like you could not swap in any other cat and get the same picture. The key question: does the image show you a *someone* with a personality, or merely a *something* in a generic pose?

### 3. Emotional Specificity

Does the image provoke a precise, pointed feeling — not a vague "aww" but a specific laugh, gasp, or moment of recognition? The best cat pictures make someone stop scrolling, lean in, or send the picture to a friend because it made them feel something they want to share. Images that produce only mild, undifferentiated warmth score low. The key question: does this image carry enough specificity to land with emotional force?

## Use Cases

- **Content platforms** — Surface the most engaging cat images from large volumes of uploads, prioritizing moment-driven content over generic pet photos.
- **Social feeds** — Rank images so that the pictures rising to the top are the ones that make people stop scrolling and feel something.
- **Pet photo communities** — Celebrate the images that spark recognition and conversation — the ones where someone comments "my cat does the EXACT same thing."
- **Content curation** — Filter and sort user-submitted cat photos for newsletters, compilations, or featured content by identifying the images with the most life in them.

## Philosophy

This function does not reward beauty, production value, or adherence to any formula. It rewards aliveness. A blurry photo of a cat caught mid-leap off a refrigerator is worth more than a studio-quality portrait of a cat lounging on a velvet pillow. The question is never "is this a good photo?" The question is: "is something *happening* here?" Images where the cat could be any cat, in any place, at any time rank lowest. Images where a real, specific, irreplaceable animal has been caught in a real, specific, unrepeatable instant rank highest.