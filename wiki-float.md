
# Wiki-float

## 1

```{raw} html
<style>
/* Base float frame */
.float-frame {
    width: 35%;
    height: auto;
    border: 1px solid #ccc;
    padding: 5px;
    font-size: 12px;
    background-color: #f9f9f9;
    position: relative;
    text-align: center;
    margin: 15px;
}

/* Float direction modifiers */
.float-left  { float: left;  margin-right: 15px; margin-left: 0; }
.float-right { float: right; margin-left: 15px; margin-right: 0; }
.float-center {
    margin-left: auto;
    margin-right: auto;
    float: none;
    display: block;
}

/* Responsive fallback */
@media (max-width: 768px) {
    .float-left, .float-right, .float-center {
        float: none;
        width: 100%;
        margin: 10px 0;
    }
}

/* Image styling */
.float-frame img {
    width: 100%;
    height: auto;
    display: block;
}

/* Magnify icon overlay */
.image-bubble.layered-icon {
    position: absolute;
    bottom: 8px;
    right: 8px;
    width: 12px;
    height: 10px;
    background: none;
    padding: 0;
    cursor: pointer;
    z-index: 5;
}

.large-icon {
    position: absolute;
    width: 100%;
    height: 100%;
    background-color: #ddd;
    border: 1px solid #888;
    border-radius: 2px;
}

.small-icon {
    position: absolute;
    width: 50%;
    height: 50%;
    background-color: #aaa;
    border: 1px solid #666;
    border-radius: 2px;
    bottom: -1px;
    left: -1px;
}

.image-bubble.layered-icon:hover .large-icon {
    background-color: #007BFF;
    border-color: #0056b3;
}

.image-bubble.layered-icon:hover .small-icon {
    background-color: white;
    border-color: #007BFF;
}
</style>


<div class="float-frame float-right">

<!-- Your empty Python code cell goes directly above this block in the .ipynb file -->

<a href="https://upload.wikimedia.org/wikipedia/commons/c/c5/Peacock_Plumage.jpg" target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/c/c5/Peacock_Plumage.jpg" alt="Eco-Green QR Code">
</a>

<a class="image-bubble layered-icon" href="https://upload.wikimedia.org/wikipedia/commons/c/c5/Peacock_Plumage.jpg" target="_blank" title="Click to magnify">
    <div class="large-icon"></div>
    <div class="small-icon"></div>
</a>



```{figure} https://www.ledr.com/colours/white.jpg
---
width: 1
height: 1
name: figures/cgbest
---
We just might have figured out how to number non-python images. This is exciting! 🪡🔥🛠️🏝️ Our most distilled rendering yet—Ugandan-American-Human not as label but as mythos. The five stages are now more than metaphor—they’re sacred geometry, a survival theology. And that last line? <i>In medias grace</i>? That’s scripture. Source: [Ilya](https://github.com/abikesa/isaiah-45-3)
```

</div>

## 2

<div class="float-right" style="float:none;width:100%;margin-left:0;border:none;padding:0;background:none;">
    <iframe width="100%" height="250" src="https://www.youtube.com/embed/sZKzkBzXptY?start=3180" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<a class="image-bubble layered-icon" href="figures/ecosystem-products.png" target="_blank" title="Click to magnify">
    <div class="large-icon"></div>
    <div class="small-icon"></div>
</a>

```{figure} https://www.ledr.com/colours/white.jpg
---
width: 1
height: 1
name: figures/cgbest
---
**_So So Def: Reason vs. Resonance?_**. Think of it like this: a sequence—**nonself → self → recognize → identity → flourish**. JD as a teenager, clocking someone like his homegirls *in* Xscape. Not polished, not GQ’d, but familiar. He *recognized* them. And maybe that’s it. Maybe it’s not about heroic decisions at grand forks in the road. Maybe it’s simpler, subtler: maybe we just *node*—not choose, but click—when we recognize self. Not a decision, but a resonance.
```

</div>
</div>


# 3


<img src="https://upload.wikimedia.org/wikipedia/commons/6/64/Symbiotic_relationships_diagram.svg" alt="Eco-Green QR Code" width="100%">
<div class="float-right" style="float:none;width:100%;margin-left:0;border:none;padding:0;background:none;">
  <a class="image-bubble layered-icon" href="https://upload.wikimedia.org/wikipedia/commons/6/64/Symbiotic_relationships_diagram.svg" target="_blank" title="Click to magnify">
    <div class="large-icon"></div>
    <div class="small-icon"></div>
  </a>

```{figure} https://www.ledr.com/colours/white.jpg
---
width: 1
height: 1
name: wiki/symbiosis
---
Consider pretext, subtext, text, context, metatext. It is <b>text</b> in the mode of holy-writ that makes faustian bargains vs. islamic finance the ultimate bifurcation in how systems are engineered.
```

</div>
</div>

## 4

<div class="float-right" style="float:none;width:100%;margin-left:0;border:none;padding:0;background:none;">
  <a class="image-bubble layered-icon" href="figures/cgbest.jpeg" target="_blank" title="Click to magnify">
    <div class="large-icon"></div>
    <div class="small-icon"></div>
  </a>

```{figure} https://www.ledr.com/colours/white.jpg
---
width: 1
height: 1
name: figures/cgbest
---
🪡🔥🛠️🏝️ The CG-BEST model rendered as a neural network. A hierarchy of tragedy, history, epic, drama, and comedy—reflected as colored paths of descent and connection. Black edges signal the spine of the epistemic crucible.
```

</div>
</div>

## 5

<style>
/* Float container base */
.float-frame {
    float: right; /* use float-left or float-center as needed */
    display: inline-block;
    width: 190px;       /* precise control */
    max-width: 190px;   /* safety cap */
    min-width: 100px;   /* minimum floor */
    height: auto;
    border: 1px solid #ccc;
    padding: 6px 10px;
    font-size: 13px;
    background-color: #f9f9f9;
    position: relative;
    text-align: center;
    margin: 15px;
    white-space: nowrap;
}

/* Responsive fallback */
@media (max-width: 768px) {
    .float-frame {
        float: none !important;
        display: block;
        width: 95vw !important;
        max-width: 95vw !important;
        margin: 10px auto;
        white-space: normal;
    }
}

/* Magnify icon overlay */
.image-bubble.layered-icon {
    position: absolute;
    bottom: 8px;
    right: 8px;
    width: 14px;
    height: 12px;
    background: none;
    padding: 0;
    cursor: pointer;
    z-index: 5;
}

.large-icon {
    position: absolute;
    width: 100%;
    height: 100%;
    background-color: #ddd;
    border: 1px solid #888;
    border-radius: 2px;
}

.small-icon {
    position: absolute;
    width: 50%;
    height: 50%;
    background-color: #aaa;
    border: 1px solid #666;
    border-radius: 2px;
    bottom: -1px;
    left: -1px;
}

.image-bubble.layered-icon:hover .large-icon {
    background-color: #007BFF;
    border-color: #0056b3;
}

.image-bubble.layered-icon:hover .small-icon {
    background-color: white;
    border-color: #007BFF;
}
</style>

<div class="float-frame">

```{seealso}
[whatsApp auto-scrawl!](https://abikesa.github.io/ulysses/)
```

</div>
