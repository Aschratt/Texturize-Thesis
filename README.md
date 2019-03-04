# Master's Thesis

This repository will soon contain the document sources for my Master's Thesis *A Framework for example-based Synthesis of Materials for Physically Based Rendering*. Please refer to [this repository](https://github.com/Aschratt/Texturize) for the project sources and [this one](https://github.com/Aschratt/Texturize-Dataset) for the dataset. You can download a printable version from [Qucosa®](https://nbn-resolving.de/urn:nbn:de:bsz:ch1-qucosa2-331788), the document and publication server of the Federal State of Saxony.

## Abstract

In computer graphics, textures are used to create detail along geometric surfaces. They are less computationally expensive than geometry, but this efficiency is traded for greater memory demands, especially with large output resolutions. Research has shown, that textures can be synthesized from low-resolution exemplars, reducing overall runtime memory cost and enabling applications, like remixing existing textures to create new, visually similar representations.

In many modern applications, textures are not limited to simple images, but rather represent geometric detail in different ways, that describe how lights interacts at a certain point on a surface. Physically Based Rendering (PBR) is a technique, that employs complex lighting models to create effects like self-shadowing, realistic reflections or subsurface scattering. A set of multiple textures is used to describe what is called a *material*.

In this thesis, example-based texture synthesis is extended to physical lighting models to create a physically based material synthesizer. It introduces a framework that is capable of utilizing multiple texture maps to synthesize new representations from existing material exemplars. The framework is then tested with multiple exemplars from different texture categories, to prospect synthesis performance in terms of quality and computation time. 

The synthesizer works in *uv* space, enabling to re-use the same exemplar material at runtime with different *uv* maps, reducing memory cost, whilst increasing visual variety and minimizing repetition artifacts. The thesis shows, that this can be done effectively, without introducing inconsistencies like seams or discontinuities under dynamic lighting scenarios.

## Cite

If you want to cite this work, use the following BibTeX:

    @MASTERSTHESIS {
        author  = "Carsten Rudolph",
        title   = "A Framework for example-based Synthesis of Materials for Physically Based Rendering",
        school  = "Chemnitz University of Technology",
        year    = "2018",
        type    = "Master's Thesis",
        address = "Technische Universität Chemnitz, Fakultät für Informatik, Straße der Nationen 62, D-09111 Chemnitz",
        month   = "aug",
        note    = "https://nbn-resolving.de/urn:nbn:de:bsz:ch1-qucosa2-331788"
    }
