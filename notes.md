---
layout: page
title: Notes
permalink: /notes/
---


# Notes


Fast, informal notes: ideas, lessons learned, gotchas, links with commentary.


## Today’s scratchpad
- [ ] Tackle input remapping in prototype
- [ ] Investigate physics timestep jitter
- [ ] Link: https://example.com/great-article (short takeaway here)


## Snippets
```csharp
// Example (Unity): simple movement snippet
void Update(){
var h = Input.GetAxis("Horizontal");
var v = Input.GetAxis("Vertical");
transform.Translate(new Vector3(h,0,v) * 5f * Time.deltaTime);
}
